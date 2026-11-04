# Gausia Committee Bangladesh — Website + Admin Panel

## Project files
- `index.html` — public homepage
- `admin.html` — secure Admin Panel launcher (opens the Apps Script-hosted panel)
- `css/style.css` — responsive public-site styling
- `js/main.js` — navigation and published-content rendering
- `js/config.js` — public Apps Script API URL (set this after deployment)
- `apps-script/Code.gs` — Google Apps Script backend
- `apps-script/Admin.html` — Admin Panel interface; create an HTML file named `Admin` in Apps Script and paste this file's contents
- `quiz.html` — separate runnable copy of the existing quiz
- `quiz-source-original.md` — exact original uploaded quiz source backup

## What the Admin Panel can manage
After setup, the Super Admin can add, edit, publish/draft and delete notices, events/news, committee member entries, gallery entries, contact information, and Homepage content entries. Published content is displayed on the public homepage. Draft entries remain private to the Admin Panel. Static homepage content remains as a fallback if the backend is unavailable.

বাংলায় পরবর্তী ধাপের বিস্তারিত নির্দেশিকা: `BACKEND-SETUP-BN.md`

## Setup: Google Apps Script backend
1. Create a new Google Sheet using the Google account that will own the website data. (The script can also create its own spreadsheet automatically.)
2. Open `script.google.com` and create a **new standalone Apps Script project**.
3. In the Apps Script editor, create/replace `Code.gs` with the full contents of `apps-script/Code.gs`.
4. Add a new HTML file in the Apps Script project named exactly `Admin` (Apps Script will show `Admin.html`). Paste the full contents of `apps-script/Admin.html` into it.
5. In `setAdminCredentialsOnce()` in `Code.gs`, replace `CHANGE_THIS_NOW` with a strong password of at least 12 characters. The default username is `admin`; you can change it in that function.
6. Select `setAdminCredentialsOnce` in the function dropdown and click **Run**. Approve the requested permissions. The script stores the salted password hash in Script Properties and creates the Google Sheet automatically on first data use.
7. Run `initializeWebsiteDatabase` once to create and format the Google Sheets database.
8. Immediately remove the real password from the source by deleting the `setAdminCredentialsOnce()` function (or replacing its password with the placeholder again), then save. The stored hash and salt remain in Script Properties. Do not share the Apps Script project with untrusted people.
9. Deploy → **New deployment** → type **Web app**. Set **Execute as: Me** and **Who has access: Anyone**; deploy and copy the Web App URL ending in `/exec`. This public endpoint is required for the public GitHub Pages site. Public read access returns only published content; all admin operations run inside the Apps Script-hosted Admin page through `google.script.run` and require a server-validated login token.
10. Open your website's `admin.html`, paste the Web App URL, click **URL সংরক্ষণ**, then **Admin Panel খুলুন**. The login page opens on Google's Apps Script host. Log in using your chosen username and password.
11. Put the same Web App URL in `js/config.js` as the value of `window.GAUSIA_API_URL`, commit and push the change to GitHub Pages. Example:
   `window.GAUSIA_API_URL = 'https://script.google.com/macros/s/DEPLOYMENT_ID/exec';`
12. If you edit `Code.gs` or `Admin.html` later, use Deploy → Manage deployments → Edit → New version → Deploy.

## Security / operational notes
- Admin login and write operations are handled by the Apps Script-hosted page. Passwords are not sent in public URL query strings and must never be placed in public website JavaScript.
- The admin session token is stored only in the Apps Script cache and expires after six hours. If it expires, log in again.
- The Web App URL is public by design. Only published content is exposed to the public website.
- Public read uses JSONP for compatibility with GitHub Pages and Apps Script. Admin operations use `google.script.run`, not JSONP.
- Images are currently added by public image URL; direct image-file upload, multi-user roles, password reset UI, audit history, and custom domain support are not included yet.
- Do not enter private personal information or sensitive data into public website content.

## GitHub Pages
Upload the **contents** of this folder to the root of your GitHub repository (not the ZIP file itself), commit, then enable GitHub Pages under repository Settings → Pages. The Admin Panel launcher will be at `/admin.html`.

## Quiz preservation
The quiz remains a separate `quiz.html` page. `quiz-source-original.md` preserves the exact uploaded source file. The runnable HTML was created by removing Markdown-escaping characters from the pasted source; no quiz features or business logic were intentionally changed. Keep the original backup.
