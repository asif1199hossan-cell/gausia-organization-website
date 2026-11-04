# পরবর্তী ধাপ: Google Apps Script Backend প্রস্তুত ও Homepage সংযোগ

এই ধাপে Homepage-কে Google Sheets-এ রাখা কনটেন্টের সঙ্গে যুক্ত করার ভিত্তি প্রস্তুত করা হয়েছে। GitHub Pages ওয়েবসাইট আলাদা থাকবে; Google Apps Script ডেটাবেস/API এবং Admin Panel পরিচালনা করবে।

## এই ZIP-এ যা প্রস্তুত
- `apps-script/Code.gs`: Backend API, Google Sheets database তৈরি/পড়া/লেখা এবং Super Admin authentication।
- `apps-script/Admin.html`: Apps Script-এর ভেতরে চলা Admin Panel।
- `js/config.js`: Homepage-এর Backend URL বসানোর জায়গা।
- `js/main.js`: Published notice, event, committee, gallery ও contact তথ্য Homepage-এ দেখানোর সংযোগ।
- `admin.html`: Apps Script Admin Panel খোলার লিংক সেট করার পেজ।

## Google Apps Script-এ করণীয় (আপনি পরে করবেন)
1. `script.google.com` থেকে নতুন Standalone Apps Script project খুলুন।
2. `apps-script/Code.gs`-এর কোড Apps Script-এর `Code.gs`-এ দিন।
3. Apps Script-এ HTML file তৈরি করে নাম দিন `Admin`; তাতে `apps-script/Admin.html`-এর কোড দিন।
4. `setAdminCredentialsOnce()`-এ নিজের শক্তিশালী Password বসান (কমপক্ষে ১২ অক্ষর)। Function একবার Run করে permission দিন। এরপর কোড থেকে আসল Password মুছে placeholder ফিরিয়ে দিন এবং Save করুন।
5. Function dropdown থেকে `initializeWebsiteDatabase` Run করুন। এতে `Gausia Committee Website Data` Spreadsheet ও `WebsiteContent` Sheet তৈরি হবে। Sheet ID Script Properties-এ থাকবে।
6. Deploy → New deployment → Web app: Execute as **Me**, Who has access **Anyone**। Deploy করে `/exec` URL কপি করুন।
7. GitHub Pages-এ `admin.html` খুলে URL বসিয়ে Save করুন, তারপর Admin Panel খুলে Login করুন।
8. একই URL `js/config.js`-এ বসান: `window.GAUSIA_API_URL = 'https://script.google.com/macros/s/DEPLOYMENT_ID/exec';`
9. GitHub repository-তে পরিবর্তন Commit/Push করুন। Homepage reload করে Admin Panel থেকে একটি Test Notice প্রকাশ করে যাচাই করুন।

## Database structure
`WebsiteContent` Sheet-এর কলাম: `id | kind | title | body | image | date | position | status | updatedAt`

`kind`: `notice` (নোটিশ), `event` (অনুষ্ঠান/সংবাদ), `committee` (কমিটির সদস্য), `gallery` (গ্যালারি), `page` (Homepage-এর অতিরিক্ত লেখা), `contact` (যোগাযোগ)। `status` হবে `published` অথবা `draft`; শুধু `published` কনটেন্ট Homepage-এ দেখা যাবে।

## সংযোগ পরীক্ষা
Deploy করা Web App URL-এর শেষে `?action=ping` যোগ করে খুললে `ok:true` এবং “Backend ও Google Sheets Database প্রস্তুত” বার্তা পাওয়া উচিত।

## গুরুত্বপূর্ণ নিরাপত্তা
- আসল Admin Password কখনো `js/config.js`, Homepage বা GitHub-এর public file-এ লিখবেন না।
- Apps Script project কাউকে Editor access দেবেন না, যদি তার ওপর পূর্ণ আস্থা না থাকে।
- Public endpoint শুধু Published content দেখায়; Admin-এর Save/Delete কাজ Apps Script-hosted Admin page-এর authenticated `google.script.run` দিয়ে হয়।
- ছবি আপাতত public image URL দিয়ে যুক্ত হবে; সরাসরি ফাইল আপলোড পরবর্তী উন্নয়ন।
- Backend আপনার Google Account-এ এখনো Deploy করা হয়নি; সেটি আপনার Account থেকেই করতে হবে।

## পুরোনো Quiz
`quiz.html` আলাদা রাখা হয়েছে। `quiz-source-original.md`-এ আগের আপলোড করা মূল Quiz source backup আছে। Quiz-এর Google Apps Script/Sheet-এর সঙ্গে এই Website Backend মেশাবেন না।
