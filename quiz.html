<!DOCTYPE html>
<html lang="bn">
<head>
    <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.6.0/dist/confetti.browser.min.js">
    </script>
    <script src="https://cdn.jsdelivr.net/npm/qrcode@1.5.3/build/qrcode.min.js">
    </script>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>গাউসিয়া কমিটি | কুইজ কম্পিটিশন</title>
    <style>
        :root {
            --primary: #18661F;
            --secondary: #1e3c72;
            --success: #2ecc71;
            --danger: #e74c3c;
            --gold: #f1c40f;
            --glass: rgba(255, 255, 255, 0.95);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', 'SolaimanLipi', sans-serif;
            user-select: none;
        }

        body {
            background: linear-gradient(-45deg, #18661F, #1e3c72, #2a5298, #0f2027);
            background-size: 400% 400%;
            animation: gradientBG 15s ease infinite;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: flex-start;
            padding: 20px;
            color: #333;
        }

        @keyframes gradientBG {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .main-wrapper {
            width: 100%;
            max-width: 800px;
            margin: 0 auto;
        }

        .quiz-container {
            background: var(--glass);
            border-radius: 30px;
            padding: 30px 25px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.4);
            backdrop-filter: blur(10px);
            position: relative;
            border: 1px solid rgba(255, 255, 255, 0.2);
        }

        /* ===== LOGO CENTER ===== */
        .logo-center {
            display: flex;
            justify-content: center;
            align-items: center;
            margin-bottom: 10px;
        }

        .logo {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            border: 4px solid var(--primary);
            background: white;
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.2);
            object-fit: cover;
        }

        .prize-section {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 6px;
            margin: 10px 0;
        }

        .prize-card {
            background: linear-gradient(135deg, #f8f9fa, #e9ecef);
            padding: 10px 6px;
            border-radius: 10px;
            text-align: center;
        }

        .prize-card.gold {
            background: linear-gradient(135deg, #ffe259, #ffa751);
            color: #333;
        }

        .prize-card.silver {
            background: linear-gradient(135deg, #e0e0e0, #bdbdbd);
            color: #333;
        }

        .prize-card.bronze {
            background: linear-gradient(135deg, #ffcc80, #ffa726);
            color: #333;
        }

        .prize-card .trophy { font-size: 20px; }
        .prize-card .amount { font-size: 14px; font-weight: bold; }
        .prize-card .label { font-size: 10px; color: #666; }

        /* ===== সতর্কতা বক্স ===== */
        .warning-box {
            margin: 10px 0;
            padding: 10px;
            background: #fff3cd;
            border-radius: 10px;
            border: 2px solid #ffc107;
            text-align: center;
            animation: pulseWarning 1.5s infinite alternate;
        }

        @keyframes pulseWarning {
            from { border-color: #ffc107; }
            to { border-color: #d32f2f; }
        }

        .warning-box p {
            font-size: 14px;
            font-weight: bold;
            color: #856404;
            margin: 0;
        }

        .warning-box .sub-text {
            font-size: 11px;
            color: #856404;
            margin: 4px 0 0 0;
            font-weight: normal;
        }

        /* ===== মেনু বাটন ===== */
        .menu-item .menu-btn {
            background: var(--primary);
            color: white;
            border: none;
            padding: 5px 10px;
            border-radius: 8px;
            font-size: 11px;
            cursor: pointer;
            width: 100%;
            text-align: center;
            font-weight: bold;
            transition: 0.3s;
        }

        .menu-item .menu-btn:hover {
            transform: scale(1.02);
            opacity: 0.9;
        }

        .entry-section {
            background: #f8f9fa;
            border-radius: 14px;
            padding: 14px;
            margin: 10px 0;
            border: 2px dashed var(--primary);
        }

        .entry-badge {
            display: inline-block;
            background: var(--gold);
            color: #333;
            padding: 3px 12px;
            border-radius: 20px;
            font-weight: bold;
            font-size: 12px;
            margin-bottom: 6px;
        }

        .entry-input-group {
            display: flex;
            flex-direction: column;
            gap: 6px;
        }

        .entry-input {
            padding: 10px;
            border: 2px solid #ddd;
            border-radius: 10px;
            text-align: center;
            font-size: 14px;
            font-weight: bold;
            letter-spacing: 2px;
            text-transform: uppercase;
        }

        .entry-input:focus {
            border-color: var(--primary);
            outline: none;
        }

        .btn-entry {
            padding: 10px;
            border: none;
            border-radius: 10px;
            background: linear-gradient(135deg, #2ecc71, #27ae60);
            color: white;
            font-size: 14px;
            font-weight: bold;
            cursor: pointer;
            transition: 0.3s;
        }

        .btn-entry:hover { transform: scale(1.02); }
        .btn-entry:disabled { opacity: 0.5; cursor: not-allowed; }

        .status-message {
            padding: 8px;
            border-radius: 8px;
            margin: 6px 0;
            font-weight: bold;
            font-size: 12px;
            display: none;
        }

        .status-message.success { display: block; background: #d4edda; color: #155724; }
        .status-message.error { display: block; background: #f8d7da; color: #721c24; }
        .status-message.pending { display: block; background: #fff3cd; color: #856404; }

        .input-group {
            display: flex;
            flex-direction: column;
            gap: 6px;
            margin-bottom: 10px;
        }

        .name-input {
            padding: 10px;
            border: 2px solid #ddd;
            border-radius: 12px;
            text-align: center;
            font-size: 14px;
            transition: 0.3s;
        }

        .name-input:focus {
            border-color: var(--primary);
            outline: none;
            box-shadow: 0 0 10px rgba(24, 102, 31, 0.2);
        }

        .btn-main {
            width: 100%;
            padding: 12px;
            border: none;
            border-radius: 12px;
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
            font-size: 15px;
            font-weight: bold;
            cursor: pointer;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
            transition: 0.2s;
        }

        .btn-main:disabled { opacity: 0.5; cursor: not-allowed; }

        .lifelines-bar {
            display: flex;
            flex-wrap: wrap;
            gap: 6px;
            justify-content: center;
            margin: 8px 0 12px 0;
        }

        .lifeline-btn {
            padding: 4px 12px;
            border: none;
            border-radius: 20px;
            font-size: 11px;
            font-weight: bold;
            cursor: pointer;
            transition: 0.3s;
            background: #eee;
            color: #555;
        }

        .lifeline-btn:hover:not(:disabled) { transform: scale(1.05); }
        .lifeline-btn:disabled { opacity: 0.4; cursor: not-allowed; transform: none; }

        .lifeline-btn.ll-5050 { background: #e1f5fe; color: #0288d1; }
        .lifeline-btn.ll-time { background: #fff3e0; color: #e65100; }
        .lifeline-btn.ll-answer { background: #e8f5e9; color: #2e7d32; }
        .lifeline-btn.ll-poll { background: #fce4ec; color: #c62828; }
        .lifeline-btn.ll-guard { background: #f3e5f5; color: #6a1b9a; }
        .lifeline-btn.ll-skip { background: #2196F3; color: white; }
        .lifeline-btn.ll-hint { background: #9C27B0; color: white; }

        .lifeline-btn.active { box-shadow: 0 0 15px rgba(0, 0, 0, 0.2); }
        .lifeline-btn.ll-5050.active { background: #0288d1; color: white; }
        .lifeline-btn.ll-time.active { background: #e65100; color: white; }
        .lifeline-btn.ll-answer.active { background: #2e7d32; color: white; }
        .lifeline-btn.ll-poll.active { background: #c62828; color: white; }
        .lifeline-btn.ll-guard.active { background: #6a1b9a; color: white; }
        .lifeline-btn.ll-skip.active { background: #0d47a1; color: white; }
        .lifeline-btn.ll-hint.active { background: #4a148c; color: white; }

        .buffs-panel {
            display: flex;
            gap: 6px;
            justify-content: center;
            margin-bottom: 10px;
            flex-wrap: wrap;
        }

        .buff-badge {
            display: none;
            padding: 4px 12px;
            border-radius: 15px;
            font-size: 10px;
            font-weight: bold;
            animation: popIn 0.3s ease-out;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        .buff-5050 { background: #e1f5fe; color: #0288d1; border: 1px solid #0288d1; }
        .buff-guard { background: #f3e5f5; color: #6a1b9a; border: 1px solid #6a1b9a; animation: pulseGuard 0.8s infinite alternate; }
        .buff-double { background: #ffeb3b; color: #333; border: 1px solid #f57f17; }
        .buff-skip { background: #2196F3; color: white; border: 1px solid #0d47a1; }
        .buff-hint { background: #9C27B0; color: white; border: 1px solid #4a148c; }

        @keyframes popIn {
            from { transform: scale(0); opacity: 0; }
            to { transform: scale(1); opacity: 1; }
        }

        @keyframes pulseGuard {
            from { transform: scale(1); }
            to { transform: scale(1.05); }
        }

        .stats-row {
            display: flex;
            justify-content: space-between;
            margin-bottom: 10px;
            align-items: center;
        }

        .badge {
            padding: 5px 12px;
            border-radius: 10px;
            font-weight: bold;
            font-size: 12px;
        }

        .step-badge { background: #e8f5e9; color: var(--primary); }
        .timer-badge { background: #fff0f0; color: var(--danger); transition: 0.3s; }
        .timer-badge.pulse { animation: pulse 0.5s infinite alternate; }

        @keyframes pulse {
            from { transform: scale(1); }
            to { transform: scale(1.08); }
        }

        .question-text {
            font-size: 17px;
            color: #2c3e50;
            margin-bottom: 14px;
            text-align: left;
            font-weight: bold;
            line-height: 1.4;
        }

        .options-grid {
            display: grid;
            gap: 8px;
            margin-bottom: 10px;
        }

        .option-btn {
            padding: 11px 14px;
            background: white;
            border: 2px solid #ececec;
            border-radius: 12px;
            cursor: pointer;
            text-align: left;
            font-size: 14px;
            font-weight: 500;
            transition: 0.2s;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .option-btn:hover:not(.disabled) {
            border-color: var(--secondary);
            background: #f8fafd;
        }

        .option-btn.hidden-option {
            opacity: 0.2;
            pointer-events: none;
            text-decoration: line-through;
        }

        .correct {
            background: var(--success) !important;
            color: white !important;
            border-color: var(--success) !important;
        }

        .wrong {
            background: var(--danger) !important;
            color: white !important;
            border-color: var(--danger) !important;
            animation: shake 0.4s;
        }

        .disabled { pointer-events: none; }

        .poll-percentage {
            font-size: 11px;
            font-weight: bold;
            color: #7f8c8d;
            display: none;
        }

        .correct .poll-percentage,
        .wrong .poll-percentage { color: white; }

        .progress-bar {
            height: 5px;
            background: #eee;
            border-radius: 10px;
            margin-bottom: 14px;
            overflow: hidden;
        }

        #progressFill {
            height: 100%;
            width: 0%;
            background: linear-gradient(90deg, var(--success), #27ae60);
            transition: 0.4s;
        }

        .fade-in { animation: fadeIn 0.4s ease-in; }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @keyframes shake {
            0%, 100% { transform: translateX(0); }
            25% { transform: translateX(-6px); }
            75% { transform: translateX(6px); }
        }

        .menu-container {
            position: absolute;
            top: 12px;
            right: 18px;
            z-index: 10;
        }

        .three-dot-btn {
            background: none;
            border: none;
            font-size: 20px;
            cursor: pointer;
            color: #666;
            padding: 4px 8px;
        }

        .menu-dropdown {
            display: none;
            position: absolute;
            top: 30px;
            right: 0;
            background: white;
            border-radius: 12px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            width: 190px;
            padding: 8px;
            border: 1px solid #eee;
            text-align: left;
            animation: fadeIn 0.2s ease-out;
        }

        .menu-dropdown.show { display: block; }

        .menu-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 5px;
            font-size: 12px;
            font-weight: bold;
            color: #444;
            border-bottom: 1px solid #f5f5f5;
        }

        .menu-item:last-child { border-bottom: none; }

        .theme-toggle-btn,
        .audio-toggle-btn {
            background: #eee;
            border: none;
            padding: 3px 8px;
            border-radius: 20px;
            cursor: pointer;
            font-size: 12px;
        }

        /* Admin Panel */
        .admin-panel {
            background: #f8f9fa;
            border-radius: 14px;
            padding: 14px;
            margin-top: 10px;
            display: none;
            text-align: left;
        }

        .admin-panel h4 { color: var(--primary); margin-bottom: 6px; font-size: 14px; }

        .admin-stats {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 6px;
            margin: 6px 0;
        }

        .stat-box {
            background: white;
            padding: 6px;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .stat-box .number { font-size: 18px; font-weight: bold; color: var(--primary); }
        .stat-box .label { font-size: 9px; color: #666; }

        .admin-action-btn {
            width: 100%;
            padding: 7px;
            margin: 3px 0;
            border: none;
            border-radius: 8px;
            font-weight: bold;
            cursor: pointer;
            font-size: 12px;
        }

        .btn-start-competition { background: var(--success); color: white; }
        .btn-end-competition { background: var(--danger); color: white; }
        .btn-declare-winners { background: var(--gold); color: #333; }
        .btn-generate-code { background: #9b59b6; color: white; }

        .admin-leaderboard {
            margin-top: 10px;
            background: white;
            border-radius: 10px;
            padding: 10px;
            max-height: 300px;
            overflow-y: auto;
        }

        .admin-leaderboard h5 {
            color: var(--secondary);
            font-size: 13px;
            margin-bottom: 8px;
            text-align: center;
            border-bottom: 1px solid #eee;
            padding-bottom: 5px;
        }

        .admin-lb-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 4px 8px;
            border-radius: 6px;
            margin-bottom: 2px;
            font-size: 12px;
            background: rgba(0, 0, 0, 0.02);
        }

        .admin-lb-item .rank { font-weight: bold; color: #888; width: 20px; font-size: 11px; }
        .admin-lb-item .name { flex: 1; font-weight: 500; margin: 0 4px; font-size: 12px; }
        .admin-lb-item .score { font-weight: bold; color: var(--primary); background: #e8f5e9; padding: 1px 8px; border-radius: 12px; font-size: 11px; }

        .admin-lb-item.top1 { background: linear-gradient(135deg, #ffe259, #ffa751); color: #333; }
        .admin-lb-item.top1 .score { background: #fff; }
        .admin-lb-item.top2 { background: linear-gradient(135deg, #e0e0e0, #bdbdbd); color: #333; }
        .admin-lb-item.top2 .score { background: #fff; }
        .admin-lb-item.top3 { background: linear-gradient(135deg, #ffcc80, #ffa726); color: #333; }
        .admin-lb-item.top3 .score { background: #fff; }

        .admin-lb-empty {
            text-align: center;
            color: #999;
            padding: 15px 0;
            font-size: 12px;
        }

        .result-score {
            background: #f0f7f1;
            padding: 16px;
            border-radius: 16px;
            margin: 14px 0;
        }

        .result-score h1 {
            color: var(--success);
            font-size: 36px;
            margin-top: 4px;
            text-align: center;
        }

        .winner-announce {
            background: linear-gradient(135deg, #ffe259, #ffa751);
            padding: 12px 16px;
            border-radius: 12px;
            margin: 10px 0 15px 0;
            text-align: center;
            color: #333;
            font-weight: bold;
            font-size: 14px;
            box-shadow: 0 4px 15px rgba(241, 196, 15, 0.3);
        }

        .winner-announce .date {
            font-size: 16px;
            color: #1a4a2a;
            margin-top: 2px;
        }

        .winner-announce .label {
            font-size: 11px;
            color: #555;
            font-weight: normal;
        }

        .mystery-overlay {
            position: fixed;
            inset: 0;
            background: rgba(0, 0, 0, 0.85);
            z-index: 99999;
            display: flex;
            justify-content: center;
            align-items: center;
            backdrop-filter: blur(5px);
        }

        .mystery-box-card {
            background: linear-gradient(135deg, #ffe259, #ffa751);
            padding: 35px 25px;
            border-radius: 24px;
            text-align: center;
            box-shadow: 0 15px 50px rgba(0, 0, 0, 0.5);
            width: 90%;
            max-width: 380px;
            animation: popIn 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            color: #333;
        }

        .mystery-gift-icon {
            font-size: 70px;
            cursor: pointer;
            animation: bounce 1s infinite alternate;
            transition: 0.3s;
        }

        .mystery-gift-icon:hover { transform: scale(1.1); }

        @keyframes bounce {
            from { transform: translateY(0); }
            to { transform: translateY(-15px); }
        }

        /* ===== ডার্ক মোড ===== */
        body.dark-mode {
            background: linear-gradient(-45deg, #0a2e0f, #101d33, #15294a, #050a0c);
        }

        .dark-mode .quiz-container {
            background: rgba(30, 30, 30, 0.96);
            color: #e0e0e0;
            border-color: #333;
        }

        .dark-mode .question-text { color: #ffffff; }
        .dark-mode .option-btn { background: #2d2d2d; border-color: #444; color: #eee; }
        .dark-mode .name-input { background: #333; color: #fff; border-color: #555; }
        .dark-mode .entry-section { background: #2d2d2d; border-color: #555; }
        .dark-mode .prize-card { background: #2d2d2d; color: #ddd; }
        .dark-mode .lifeline-btn { background: #3d3d3d; color: #aaa; }
        .dark-mode .lifeline-btn.ll-5050 { background: #1a3a4a; color: #4fc3f7; }
        .dark-mode .lifeline-btn.ll-time { background: #4a2a1a; color: #ffa726; }
        .dark-mode .lifeline-btn.ll-answer { background: #1a3a1a; color: #66bb6a; }
        .dark-mode .lifeline-btn.ll-poll { background: #4a1a1a; color: #ef5350; }
        .dark-mode .lifeline-btn.ll-guard { background: #2a1a3a; color: #ab47bc; }
        .dark-mode .lifeline-btn.ll-skip { background: #1a3a5a; color: #64b5f6; }
        .dark-mode .lifeline-btn.ll-hint { background: #3a1a4a; color: #ce93d8; }
        .dark-mode .lifeline-btn.ll-5050.active { background: #0288d1; color: white; }
        .dark-mode .lifeline-btn.ll-time.active { background: #e65100; color: white; }
        .dark-mode .lifeline-btn.ll-answer.active { background: #2e7d32; color: white; }
        .dark-mode .lifeline-btn.ll-poll.active { background: #c62828; color: white; }
        .dark-mode .lifeline-btn.ll-guard.active { background: #6a1b9a; color: white; }
        .dark-mode .lifeline-btn.ll-skip.active { background: #0d47a1; color: white; }
        .dark-mode .lifeline-btn.ll-hint.active { background: #4a148c; color: white; }
        .dark-mode .menu-dropdown { background: #252525; border-color: #444; color: #fff; }
        .dark-mode .menu-item { color: #ddd; border-color: #444; }
        .dark-mode .winner-announce { background: linear-gradient(135deg, #2d2d2d, #3d3d3d); color: #f1c40f; border: 1px solid #f1c40f; }
        .dark-mode .winner-announce .date { color: #f1c40f; }
        .dark-mode .winner-announce .label { color: #aaa; }
        .dark-mode .mystery-box-card { background: linear-gradient(135deg, #2d2d2d, #3d3d3d); color: #fff; border: 1px solid #f1c40f; }
        .dark-mode .admin-leaderboard { background: #2d2d2d; color: #ddd; }
        .dark-mode .admin-leaderboard h5 { border-color: #444; }
        .dark-mode .admin-lb-item { background: rgba(255, 255, 255, 0.03); color: #ddd; }
        .dark-mode .admin-lb-item .score { background: #1a3a1a; color: #2ecc71; }
        .dark-mode .admin-lb-item.top1 .score { background: #333; color: #f1c40f; }
        .dark-mode .admin-lb-item.top2 .score { background: #333; color: #bdbdbd; }
        .dark-mode .admin-lb-item.top3 .score { background: #333; color: #ffa726; }

        /* ===== ডার্ক মোডে সতর্কতা ===== */
        .dark-mode .warning-box {
            background: #2d2d2d !important;
            border-color: #f1c40f !important;
        }

        .dark-mode .warning-box p {
            color: #f1c40f !important;
        }

        .dark-mode .warning-box .sub-text {
            color: #aaa !important;
        }

        .dark-mode .menu-item .menu-btn {
            background: #1a3a1a;
            color: #66bb6a;
        }

        .dark-mode .menu-item .menu-btn:hover {
            background: #2a4a2a;
        }

        /* ===== রেস্পন্সিভ ===== */
        @media (max-width: 480px) {
            .prize-section { grid-template-columns: 1fr 1fr 1fr; gap: 4px; }
            .prize-card .trophy { font-size: 18px; }
            .prize-card .amount { font-size: 12px; }
            .quiz-container { padding: 15px 12px; }
            .logo { width: 60px; height: 60px; }
            .winner-announce { font-size: 12px; padding: 10px 12px; }
            .winner-announce .date { font-size: 14px; }
            .lifeline-btn { font-size: 10px; padding: 3px 8px; }
            .mystery-box-card { padding: 25px 15px; }
            .mystery-gift-icon { font-size: 50px; }
            .menu-dropdown { width: 180px; right: -10px; }
        }

        .admin-leaderboard::-webkit-scrollbar { width: 3px; }
        .admin-leaderboard::-webkit-scrollbar-track { background: rgba(0, 0, 0, 0.05); border-radius: 10px; }
        .admin-leaderboard::-webkit-scrollbar-thumb { background: var(--primary); border-radius: 10px; }

        /* ===== দ্বি-স্তর অ্যাডমিন: মডারেটর মোডে সুপার-অ্যাডমিন-শুধু নিয়ন্ত্রণ লুকানো ===== */
        body.moderator-mode .super-only { display: none !important; }
        .custom-q-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: #f8f9fa;
            padding: 5px 8px;
            border-radius: 6px;
            margin-bottom: 3px;
            font-size: 11px;
        }
        .custom-q-item button {
            background: #e74c3c;
            color: white;
            border: none;
            padding: 2px 8px;
            border-radius: 6px;
            font-size: 10px;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <!-- ===== 🌟 স্প্ল্যাশ/ইন্ট্রো স্ক্রিন ===== -->
    <div id="splashScreen" style="position:fixed; inset:0; z-index:999999; display:flex; flex-direction:column; align-items:center; justify-content:center; background:linear-gradient(-45deg, #18661F, #1e3c72, #2a5298, #0f2027); background-size:400% 400%; animation: gradientBG 6s ease infinite; transition: opacity 0.5s ease;">
        <img src="https://i.imgur.com/mXYuZAS.jpeg" style="width:90px; height:90px; border-radius:50%; border:4px solid white; box-shadow:0 8px 25px rgba(0,0,0,0.3); animation: popIn 0.6s ease-out;" alt="লোগো">
        <div style="color:white; font-weight:bold; margin-top:14px; font-size:16px; text-align:center;">গাউসিয়া কমিটি বাংলাদেশ</div>
        <div style="color:#f1c40f; font-weight:bold; font-size:13px; margin-top:2px;">কুইজ কম্পিটিশন ২০২৬</div>
        <div style="color:#ddd; font-size:11px; margin-top:14px;">⏳ লোড হচ্ছে...</div>
    </div>

    <div class="main-wrapper">
        <div class="quiz-container">
            <!-- Menu -->
            <div class="menu-container">
                <button class="three-dot-btn" onclick="toggleMenu(event)">⋮</button>
                <div class="menu-dropdown" id="menuDropdown">
                    <!-- ===== নিয়মাবলী ===== -->
                    <div class="menu-item" style="border-bottom:1px solid #f5f5f5; justify-content:center; padding-bottom:6px; margin-bottom:4px;">
                        <button class="menu-btn" onclick="showRules()">📋 কম্পিটিশনের নিয়মাবলী</button>
                    </div>
                    <div class="menu-item" style="justify-content:center; padding-bottom:6px;">
                        <button class="menu-btn" style="background:#0288d1;" onclick="showDeveloperInfo()">👨‍💻 ডেভেলপার পরিচিতি</button>
                    </div>
                    <div class="menu-item" style="justify-content:center; padding-bottom:6px;">
                        <button class="menu-btn" style="background:#6a1b9a;" onclick="showAboutCommittee()">🕌 গাউসিয়া কমিটি বাংলাদেশ</button>
                    </div>
                    <div class="menu-item" style="justify-content:center; padding-bottom:6px;">
                        <button class="menu-btn" style="background:#e67e22;" onclick="showFAQ()">❓ FAQ</button>
                    </div>
                    <div class="menu-item" style="justify-content:center; padding-bottom:6px;">
                        <button class="menu-btn" style="background:#16a085;" onclick="focusAiAssistant()">🤖 AI সহায়তা</button>
                    </div>
                    <div class="menu-item" style="justify-content:center; padding-bottom:6px;">
                        <button class="menu-btn" style="background:#2c3e50;" onclick="showContact()">📞 যোগাযোগ</button>
                    </div>
                    <div class="menu-item" style="justify-content:center; padding-bottom:6px;">
                        <button class="menu-btn" style="background:#f39c12;" onclick="showPrizeDetails()">🏆 পুরস্কারের বিবরণ</button>
                    </div>
                    <div class="menu-item" style="justify-content:center; padding-bottom:6px;">
                        <button class="menu-btn" style="background:#2980b9;" onclick="showSchedule()">📅 সময়সূচি</button>
                    </div>
                    <div class="menu-item" style="justify-content:center; padding-bottom:6px;">
                        <button class="menu-btn" style="background:#27ae60;" onclick="shareCompetition()">📢 প্রতিযোগিতা শেয়ার করুন</button>
                    </div>
                    <div class="menu-item" style="justify-content:center; padding-bottom:6px;">
                        <button class="menu-btn" style="background:#c0392b;" onclick="downloadRules()">📥 নিয়মাবলী ডাউনলোড</button>
                    </div>
                    <div class="menu-item" style="justify-content:center; padding-bottom:6px;">
                        <button class="menu-btn" style="background:#7f8c8d;" onclick="showPrivacyPolicy()">🔒 Privacy Policy</button>
                    </div>
                    <div class="menu-item" style="justify-content:center; padding-bottom:6px;">
                        <button class="menu-btn" style="background:#7f8c8d;" onclick="showTerms()">📜 Terms & Conditions</button>
                    </div>
                    <div class="menu-item">
                        <span>সাউন্ড:</span>
                        <button class="audio-toggle-btn" onclick="toggleAudio(event)" id="audioBtn">🔊</button>
                    </div>
                    <div class="menu-item">
                        <span>থিম:</span>
                        <button class="theme-toggle-btn" onclick="toggleTheme(event)" id="themeBtn">🌙</button>
                    </div>
                    <div class="menu-item" style="border-bottom:none; justify-content:center; gap:6px;">
                        <button onclick="location.reload()" style="background:#e74c3c; color:white; border:none; padding:2px 10px; border-radius:8px; font-size:11px; cursor:pointer;">⟳</button>
                        <button onclick="showAdminPanel()" style="background:#3498db; color:white; border:none; padding:2px 10px; border-radius:8px; font-size:11px; cursor:pointer;">⚙️</button>
                    </div>
                </div>
            </div>

            <!-- Start Screen -->
            <div id="startScreen" class="fade-in">
                <div class="logo-center">
                    <img src="https://i.imgur.com/mXYuZAS.jpeg" class="logo" alt="গাউসিয়া কমিটি">
                </div>

                <h4 style="font-size:13px; text-align:center;">গাউসিয়া কমিটি বাংলাদেশ</h4>
                <h2 style="color:var(--primary); margin:2px 0 6px 0; font-size:18px; text-align:center;">কুইজ কম্পিটিশন ২০২৬</h2>
                <p style="font-weight:600; color:#666; margin-bottom:6px; font-size:11px; text-align:center;">ঘাষি মাঝির পাড়া ইউনিট</p>

                <div class="prize-section">
                    <div class="prize-card gold"><div class="trophy">🥇</div><div class="amount">৳৫,০০০</div><div class="label">১ম</div></div>
                    <div class="prize-card silver"><div class="trophy">🥈</div><div class="amount">৳৩,০০০</div><div class="label">২য়</div></div>
                    <div class="prize-card bronze"><div class="trophy">🥉</div><div class="amount">৳২,০০০</div><div class="label">৩য়</div></div>
                </div>

                <!-- ===== সতর্কতা বক্স ===== -->
                <div class="warning-box">
                    <p>⚠️ <span style="color:#d32f2f;">চুরি করলে আল্লাহ কাছে দায়বদ্ধ থাকবেন</span> ⚠️</p>
                    <p class="sub-text">কোনো অসৎ উপায়ে উত্তর খোঁজা সম্পূর্ণ নিষিদ্ধ</p>
                </div>

                <!-- ===== 📅 প্রতিযোগিতা কাউন্টডাউন (অ্যাডমিন-নিয়ন্ত্রিত সময়সূচি) ===== -->
                <div id="countdownBox" style="display:none; margin:10px 0; padding:10px; background:linear-gradient(135deg,#1e3c72,#2a5298); border-radius:12px; text-align:center; color:white; font-weight:bold; font-size:13px;"></div>

                <div class="entry-section" id="entrySection">
                    <div class="entry-badge">🎫 এন্ট্রি কোড</div>
                    <div class="entry-input-group">
                        <input type="text" id="entryCode" class="entry-input" placeholder="কোড দিন" maxlength="10">
                        <button class="btn-entry" onclick="verifyEntryCode()">🔓 ভেরিফাই</button>
                    </div>
                    <div id="entryStatus" class="status-message"></div>
                </div>

                <div style="margin-top:8px;">
                    <div class="input-group">
                        <input type="text" id="playerName" class="name-input" placeholder="আপনার নাম">
                        <input type="tel" id="playerMobile" class="name-input" placeholder="মোবাইল (01XXXXXXXXX)">
                    </div>
                    <label style="display:flex; align-items:flex-start; gap:6px; font-size:11px; background:#fff3cd; padding:8px; border-radius:8px; margin-bottom:8px; cursor:pointer;">
                        <input type="checkbox" id="honestyPledge" style="margin-top:2px;">
                        <span>✅ আমি অঙ্গীকার করছি যে আমি সততার সাথে, কোনো অসৎ উপায় অবলম্বন না করে এই কুইজে অংশগ্রহণ করব।</span>
                    </label>
                    <button class="btn-main" id="startBtn" onclick="registerAndStart()" disabled>🔒 এন্ট্রি কোড দিন</button>
                    <button class="btn-main" style="background:#7f8c8d; margin-top:8px; font-size:13px;" onclick="startPractice()">🎯 প্র্যাকটিস মোড (স্কোর সংরক্ষণ হবে না)</button>
                    <button id="hallOfFameBtn" class="btn-main" style="display:none; background:linear-gradient(135deg, #ffe259, #ffa751); color:#333; margin-top:8px; font-size:13px;" onclick="showHallOfFame()">🏅 Hall of Fame (Top 10)</button>
                </div>

                <p style="margin-top:10px; font-size:11px; color:#999; text-align:center;">👥 <span id="participantCount">০</span> জন অংশ নিয়েছেন</p>
                <p id="homeTimerDisplay" style="margin-top:4px; font-size:11px; color:var(--primary); text-align:center; font-weight:bold;"></p>
                <p style="font-size:10px; color:#888; text-align:center;">ডেভেলপার: আসিফ হোসেন নুর</p>

                <!-- ===== 🤖 AI নিয়ম সহকারী ===== -->
                <div style="margin-top:14px; background:#f8f9fa; border-radius:14px; padding:12px; border:2px dashed var(--secondary);">
                    <div style="font-weight:bold; font-size:13px; color:var(--secondary); margin-bottom:8px; text-align:center;">🤖 AI নিয়ম সহকারী</div>
                    <div id="aiChatBox" style="display:flex; flex-direction:column; max-height:150px; overflow-y:auto; margin-bottom:8px; padding:4px;"></div>
                    <div style="display:flex; gap:6px;">
                        <input type="text" id="aiQuestionInput" class="name-input" style="flex:1; padding:8px; font-size:12px;" placeholder="যেমন: সময়সীমা কত? পুরস্কার কী?">
                        <button class="btn-entry" style="width:auto; padding:8px 14px;" onclick="askAiAssistant()">➤</button>
                    </div>
                </div>
            </div>

            <!-- Quiz Content -->
            <div id="quizContent" style="display:none;">
                <div class="stats-row">
                    <div class="badge step-badge" id="stepDisplay">প্রশ্ন: ১/১০০</div>
                    <div class="badge timer-badge" id="timerBadge">⏱ <span id="time">০</span>সে.</div>
                </div>

                <div class="lifelines-bar">
                    <button class="lifeline-btn ll-5050" id="ll5050" onclick="use5050()">💡 ৫০:৫০</button>
                    <button class="lifeline-btn ll-time" id="llTime" onclick="useTimeBonus()">⏱️ +৩০সে</button>
                    <button class="lifeline-btn ll-answer" id="llAnswer" onclick="useShowAnswer()">🎯 সঠিক উত্তর</button>
                    <button class="lifeline-btn ll-poll" id="llPoll" onclick="useAudiencePoll()">👥 পোল</button>
                    <button class="lifeline-btn ll-guard" id="llGuard" onclick="useLifeGuard()">🛡️ লাইফ গার্ড</button>
                    <button class="lifeline-btn ll-skip" id="llSkip" onclick="useSkipQuestion()">⏭️ স্কিপ</button>
                    <button class="lifeline-btn ll-hint" id="llHint" onclick="useHint()">💡 হিন্ট</button>
                </div>

                <div class="buffs-panel">
                    <div id="signal5050" class="buff-badge buff-5050">💡 ৫০:৫০ অ্যাক্টিভ</div>
                    <div id="signalGuard" class="buff-badge buff-guard">🛡️ লাইফ গার্ড অন</div>
                    <div id="signalDouble" class="buff-badge buff-double">🔥 ডাবল স্কোর!</div>
                    <div id="signalSkip" class="buff-badge buff-skip">⏭️ স্কিপ রেডি!</div>
                    <div id="signalHint" class="buff-badge buff-hint">💡 হিন্ট রেডি!</div>
                </div>

                <div class="progress-bar"><div id="progressFill"></div></div>
                <img id="questionImage" style="display:none; width:100%; max-height:180px; object-fit:cover; border-radius:12px; margin-bottom:10px;" alt="প্রশ্নের ছবি">
                <h3 id="question" class="question-text"></h3>
                <div id="options" class="options-grid"></div>
                <button id="nextBtn" class="btn-main" style="display:none; margin-top:10px;" onclick="handleNext()">পরবর্তী ➜</button>
            </div>

            <!-- Result Screen -->
            <div id="resultScreen" style="display:none;" class="fade-in">
                <div class="logo-center">
                    <img src="https://i.imgur.com/mXYuZAS.jpeg" class="logo" alt="গাউসিয়া কমিটি">
                </div>

                <h2 style="color:var(--primary); font-size:20px; text-align:center;">আলহামদুলিল্লাহ!</h2>
                <div style="font-size:44px; margin:6px 0; text-align:center;">🏆</div>
                <p style="font-size:13px; text-align:center;">ধন্যবাদ, <b id="displayPlayerName" style="color:var(--secondary);"></b>!</p>

                <div class="result-score">
                    <p style="font-size:12px; color:#666; text-align:center;">আপনার স্কোর</p>
                    <h1><span id="finalScore"></span> / ১০০</h1>
                    <p style="font-size:12px; color:#666; text-align:center; margin-top:5px;" id="scoreBreakdown"></p>
                </div>

                <div id="categoryBreakdownBox" style="background:#f8f9fa; border-radius:12px; padding:10px; margin:8px 0; font-size:11px;"></div>
                <div id="achievementBox" style="background:#fff8e1; border-radius:12px; padding:10px; margin:8px 0; font-size:11px; border:1px solid var(--gold);"></div>

                <div class="winner-announce">
                    <div class="label">🏅 বিজয়ী ঘোষণা</div>
                    <div class="date" id="winnerDate">📅 শনিবার, ২০ জুন ২০২৬ | সন্ধ্যা ৭:০০ টা</div>
                    <div style="font-size:11px; color:#666; margin-top:2px; font-weight:normal;">⏳ ফলাফল ও পুরস্কার বিতরণ অনুষ্ঠানে যোগ দিন</div>
                </div>

                <p id="saveMsg" style="font-weight:bold; margin-bottom:12px; color:#f39c12; font-size:12px; text-align:center;"></p>

                <button id="reviewBtn" class="btn-main" style="display:none; background:#16a085; margin-bottom:6px; font-size:13px;" onclick="showAnswerReview()">📖 উত্তর পর্যালোচনা</button>
                <button class="btn-main" style="background:#25D366; margin-bottom:6px; font-size:13px;" onclick="shareResult()">শেয়ার 📲</button>
                <button class="btn-main" style="background:#3498db; margin-bottom:6px; font-size:13px;" onclick="downloadScoreCard()">🖼️ স্কোর কার্ড ডাউনলোড</button>
                <button class="btn-main" style="background:#8e44ad; margin-bottom:6px; font-size:13px;" onclick="downloadCertificate()">🎓 সার্টিফিকেট ডাউনলোড</button>
                <button class="btn-main" style="background:#7f8c8d; font-size:13px;" onclick="location.reload()">হোম 🔄</button>
                <canvas id="renderCanvas" style="display:none;"></canvas>
            </div>

            <!-- Admin Panel -->
            <div id="adminPanel" class="admin-panel">
                <h4>⚙️ অ্যাডমিন প্যানেল <span id="adminRoleBadge" style="font-size:10px; background:var(--gold); color:#333; padding:2px 8px; border-radius:10px; margin-left:6px;"></span></h4>

                <div class="admin-stats">
                    <div class="stat-box"><div class="number" id="adminTotal">০</div><div class="label">মোট অংশগ্রহণ</div></div>
                    <div class="stat-box"><div class="number" id="adminActive">০</div><div class="label">স্কোর দিয়েছে</div></div>
                    <div class="stat-box"><div class="number" id="adminAvg">০</div><div class="label">গড় স্কোর</div></div>
                </div>
                <div class="admin-stats">
                    <div class="stat-box"><div class="number" id="adminHigh">০</div><div class="label">সর্বোচ্চ স্কোর</div></div>
                    <div class="stat-box"><div class="number" id="adminLow">০</div><div class="label">সর্বনিম্ন স্কোর</div></div>
                    <div class="stat-box"><div class="number" id="adminCheatCount">০</div><div class="label">সতর্কতা লগ</div></div>
                </div>

                <div style="background:white; border-radius:8px; padding:8px; margin:8px 0;">
                    <div style="font-size:11px; font-weight:bold; margin-bottom:6px; text-align:center;">📊 স্কোর ডিস্ট্রিবিউশন</div>
                    <canvas id="scoreChartCanvas" width="280" height="120" style="width:100%; max-width:280px; display:block; margin:0 auto;"></canvas>
                </div>

                <input type="text" id="adminSearchInput" class="entry-input" style="text-transform:none; letter-spacing:0; margin:8px 0 6px 0;" placeholder="🔍 নাম বা মোবাইল দিয়ে খুঁজুন" oninput="updateAdminLeaderboard()">

                <div class="admin-leaderboard" id="adminLeaderboard">
                    <h5>🏆 লাইভ লিডারবোর্ড (শুধু অ্যাডমিন)</h5>
                    <div id="adminLbList">
                        <div class="admin-lb-empty">⏳ এখনো কেউ অংশ নেয়নি...</div>
                    </div>
                </div>

                <div style="background:white; border-radius:8px; padding:8px; margin:8px 0; display:flex; align-items:center; gap:6px;">
                    <span style="font-size:11px; font-weight:bold; flex:1;">⏱ সময়সীমা (মিনিট):</span>
                    <input type="number" id="adminDurationInput" min="1" style="width:60px; padding:4px; border:1px solid #ddd; border-radius:6px; text-align:center; font-size:12px;">
                    <button onclick="saveQuizDuration()" style="background:var(--primary); color:white; border:none; padding:4px 10px; border-radius:6px; font-size:11px; cursor:pointer; font-weight:bold;">সেভ</button>
                </div>

                <div class="super-only" style="background:white; border-radius:8px; padding:8px; margin:8px 0;">
                    <div style="font-size:11px; font-weight:bold; margin-bottom:6px;">📅 প্রতিযোগিতার সময়সূচি (হোমপেজে কাউন্টডাউন দেখাবে)</div>
                    <div style="display:flex; flex-direction:column; gap:6px;">
                        <label style="font-size:10px; color:#666;">শুরুর সময়:
                            <input type="datetime-local" id="adminScheduleStart" style="width:100%; padding:5px; border:1px solid #ddd; border-radius:6px; font-size:11px;">
                        </label>
                        <label style="font-size:10px; color:#666;">শেষের সময়:
                            <input type="datetime-local" id="adminScheduleEnd" style="width:100%; padding:5px; border:1px solid #ddd; border-radius:6px; font-size:11px;">
                        </label>
                        <button onclick="saveSchedule()" style="background:var(--secondary); color:white; border:none; padding:6px; border-radius:6px; font-size:11px; cursor:pointer; font-weight:bold;">সময়সূচি সেভ করুন</button>
                        <button onclick="clearSchedule()" style="background:#7f8c8d; color:white; border:none; padding:6px; border-radius:6px; font-size:11px; cursor:pointer;">সময়সূচি মুছুন (ম্যানুয়াল কন্ট্রোলে ফিরুন)</button>
                    </div>
                </div>

                <div class="super-only" style="background:white; border-radius:8px; padding:8px; margin:8px 0;">
                    <div id="cqFormTitle" style="font-size:11px; font-weight:bold; margin-bottom:6px;">➕ নতুন প্রশ্ন যোগ করুন</div>
                    <div style="display:flex; flex-direction:column; gap:6px;">
                        <input type="text" id="cqText" class="entry-input" style="text-transform:none; letter-spacing:0;" placeholder="প্রশ্ন লিখুন">
                        <input type="text" id="cqA" class="entry-input" style="text-transform:none; letter-spacing:0;" placeholder="অপশন ক">
                        <input type="text" id="cqB" class="entry-input" style="text-transform:none; letter-spacing:0;" placeholder="অপশন খ">
                        <input type="text" id="cqC" class="entry-input" style="text-transform:none; letter-spacing:0;" placeholder="অপশন গ">
                        <input type="text" id="cqD" class="entry-input" style="text-transform:none; letter-spacing:0;" placeholder="অপশন ঘ">
                        <select id="cqAns" style="padding:8px; border:2px solid #ddd; border-radius:8px; font-size:12px;">
                            <option value="a">সঠিক উত্তর: ক</option>
                            <option value="b">সঠিক উত্তর: খ</option>
                            <option value="c">সঠিক উত্তর: গ</option>
                            <option value="d">সঠিক উত্তর: ঘ</option>
                        </select>
                        <select id="cqDiff" style="padding:8px; border:2px solid #ddd; border-radius:8px; font-size:12px;">
                            <option value="easy">কঠিনতা: সহজ</option>
                            <option value="medium" selected>কঠিনতা: মধ্যম</option>
                            <option value="hard">কঠিনতা: কঠিন</option>
                        </select>
                        <input type="url" id="cqImg" class="entry-input" style="text-transform:none; letter-spacing:0;" placeholder="ছবির লিংক (ঐচ্ছিক)">
                        <div style="display:flex; gap:6px;">
                            <button id="cqSaveBtn" onclick="saveQuestionForm()" style="flex:1; background:var(--primary); color:white; border:none; padding:8px; border-radius:8px; font-size:12px; cursor:pointer; font-weight:bold;">➕ প্রশ্ন যোগ করুন</button>
                            <button id="cqCancelBtn" onclick="cancelEditQuestion()" style="display:none; background:#7f8c8d; color:white; border:none; padding:8px 12px; border-radius:8px; font-size:12px; cursor:pointer;">বাতিল</button>
                        </div>
                    </div>

                    <input type="text" id="qMgmtSearch" class="entry-input" style="text-transform:none; letter-spacing:0; margin-top:10px;" placeholder="🔍 প্রশ্ন খুঁজুন (এডিট/মুছার জন্য)" oninput="renderQuestionManagementList()">
                    <div id="questionMgmtList" style="margin-top:8px; max-height:220px; overflow-y:auto;"></div>
                </div>

                <div class="super-only" style="background:white; border-radius:8px; padding:8px; margin:8px 0;">
                    <div id="pqFormTitle" style="font-size:11px; font-weight:bold; margin-bottom:6px;">📚 Practice Mode প্রশ্ন যোগ করুন</div>
                    <div style="display:flex; flex-direction:column; gap:6px;">
                        <input type="text" id="pqText" class="entry-input" style="text-transform:none; letter-spacing:0;" placeholder="প্রশ্ন লিখুন">
                        <input type="text" id="pqA" class="entry-input" style="text-transform:none; letter-spacing:0;" placeholder="অপশন ক">
                        <input type="text" id="pqB" class="entry-input" style="text-transform:none; letter-spacing:0;" placeholder="অপশন খ">
                        <input type="text" id="pqC" class="entry-input" style="text-transform:none; letter-spacing:0;" placeholder="অপশন গ">
                        <input type="text" id="pqD" class="entry-input" style="text-transform:none; letter-spacing:0;" placeholder="অপশন ঘ">
                        <select id="pqAns" style="padding:8px; border:2px solid #ddd; border-radius:8px; font-size:12px;">
                            <option value="a">সঠিক উত্তর: ক</option>
                            <option value="b">সঠিক উত্তর: খ</option>
                            <option value="c">সঠিক উত্তর: গ</option>
                            <option value="d">সঠিক উত্তর: ঘ</option>
                        </select>
                        <div style="display:flex; gap:6px;">
                            <button id="pqSaveBtn" onclick="savePracticeQuestionForm()" style="flex:1; background:var(--primary); color:white; border:none; padding:8px; border-radius:8px; font-size:12px; cursor:pointer; font-weight:bold;">➕ যোগ করুন</button>
                            <button id="pqCancelBtn" onclick="cancelEditPracticeQuestion()" style="display:none; background:#7f8c8d; color:white; border:none; padding:8px 12px; border-radius:8px; font-size:12px; cursor:pointer;">বাতিল</button>
                        </div>
                        <div style="display:flex; gap:6px;">
                            <button onclick="exportPracticeQuestions()" style="flex:1; background:#16a085; color:white; border:none; padding:8px; border-radius:8px; font-size:12px; cursor:pointer;">📤 Export (JSON)</button>
                            <button onclick="document.getElementById('pqImportInput').click()" style="flex:1; background:#8e44ad; color:white; border:none; padding:8px; border-radius:8px; font-size:12px; cursor:pointer;">📥 Import (JSON)</button>
                            <input type="file" id="pqImportInput" accept="application/json" style="display:none;" onchange="importPracticeQuestions(event)">
                        </div>
                    </div>
                    <div id="practiceQuestionList" style="margin-top:8px; max-height:180px; overflow-y:auto;"></div>
                </div>

                <div class="super-only" style="background:white; border-radius:8px; padding:8px; margin:8px 0;">
                    <div style="font-size:11px; font-weight:bold; margin-bottom:6px;">⚙️ ফিচার সেটিংস</div>
                    <label style="display:flex; align-items:center; gap:6px; font-size:11px; margin-bottom:8px;">
                        <input type="checkbox" id="answerReviewToggle" onchange="setAnswerReviewEnabled(this.checked)">
                        📖 প্রতিযোগীদের জন্য উত্তর রিভিউ চালু রাখুন
                    </label>
                    <label style="display:flex; align-items:center; gap:6px; font-size:11px; margin-bottom:8px;">
                        <input type="checkbox" id="hallOfFameToggle" onchange="setHallOfFameVisible(this.checked)">
                        🏅 হোমপেজে Hall of Fame দেখান (সাধারণত প্রতিযোগিতা শেষ হলে অটো চালু হয়)
                    </label>
                    <div style="display:flex; align-items:center; gap:6px;">
                        <span style="font-size:11px; flex:1;">🎲 লাকি ড্রয়ের ন্যূনতম স্কোর:</span>
                        <input type="number" id="luckyDrawMinInput" min="0" style="width:60px; padding:4px; border:1px solid #ddd; border-radius:6px; text-align:center; font-size:12px;">
                        <button onclick="setLuckyDrawMinScore(parseInt(document.getElementById('luckyDrawMinInput').value,10)||0); alert('✅ সেভ হয়েছে!')" style="background:var(--primary); color:white; border:none; padding:4px 10px; border-radius:6px; font-size:11px; cursor:pointer; font-weight:bold;">সেভ</button>
                    </div>
                    <div style="display:flex; align-items:center; gap:6px; margin-top:8px;">
                        <span style="font-size:11px; flex:1;">🎨 সার্টিফিকেট রঙ/লোগো:</span>
                        <input type="color" id="certColorInput" value="#18661F" style="width:40px; height:28px; border:1px solid #ddd; border-radius:6px; padding:0;">
                        <input type="text" id="certLogoInput" maxlength="2" placeholder="🕌" style="width:40px; padding:4px; border:1px solid #ddd; border-radius:6px; text-align:center; font-size:14px;">
                        <button onclick="saveCertTemplateSettings()" style="background:var(--primary); color:white; border:none; padding:4px 10px; border-radius:6px; font-size:11px; cursor:pointer; font-weight:bold;">সেভ</button>
                    </div>
                </div>


                <button class="admin-action-btn btn-generate-code" onclick="generateEntryCode()">🎫 নতুন এন্ট্রি কোড</button>
                <div style="display:flex; align-items:center; gap:6px; margin:6px 0; background:#f8f9fa; border-radius:8px; padding:6px;">
                    <span style="font-size:11px; flex:1;">🎫📋 বাল্ক কোড সংখ্যা:</span>
                    <input type="number" id="bulkCodeCount" value="50" min="1" max="500" style="width:60px; padding:4px; border:1px solid #ddd; border-radius:6px; text-align:center; font-size:12px;">
                    <button onclick="bulkGenerateEntryCodes()" style="background:#9b59b6; color:white; border:none; padding:4px 10px; border-radius:6px; font-size:11px; cursor:pointer; font-weight:bold;">তৈরি + প্রিন্ট</button>
                </div>
                <button class="admin-action-btn btn-start-competition" onclick="startCompetition()">🚀 কম্পিটিশন স্টার্ট</button>
                <button class="admin-action-btn btn-end-competition" onclick="endCompetition()">⏹️ কম্পিটিশন বন্ধ</button>
                <button class="admin-action-btn btn-declare-winners" onclick="declareWinners()">🏅 বিজয়ী ঘোষণা</button>
                <button class="admin-action-btn" style="background:#9b59b6; color:white;" onclick="runLuckyDraw()">🎲 লাকি ড্র চালান</button>
                <button class="admin-action-btn" style="background:#2c3e50; color:white;" onclick="printMeritList()">📄 মেধা তালিকা (Merit List) PDF</button>
                <button class="admin-action-btn" style="background:#16a085; color:white;" onclick="exportCSV()">📊 CSV/Excel এক্সপোর্ট</button>
                <button class="admin-action-btn super-only" style="background:#2980b9; color:white;" onclick="backupData()">💾 ব্যাকআপ (JSON)</button>
                <button class="admin-action-btn super-only" style="background:#8e44ad; color:white;" onclick="document.getElementById('restoreFileInput').click()">♻️ রিস্টোর (JSON)</button>
                <input type="file" id="restoreFileInput" accept="application/json" style="display:none;" onchange="restoreData(event)">
                <button class="admin-action-btn" style="background:#d35400; color:white;" onclick="showCheatLogs()">🕵️ সতর্কতা/চিটিং লগ দেখুন</button>
                <button class="admin-action-btn" style="background:#c0392b; color:white;" onclick="showWrongQuestionsReport()">📉 সবচেয়ে বেশি ভুল হওয়া প্রশ্ন</button>
                <button class="admin-action-btn" style="background:#27ae60; color:white;" onclick="showAdvancedAnalytics()">📊 উন্নত এনালিটিক্স ড্যাশবোর্ড</button>
                <button class="admin-action-btn" style="background:#34495e; color:white;" onclick="printQuestionBank()">🖨️ প্রশ্ন প্রিন্ট/PDF করুন</button>
                <button class="admin-action-btn" style="background:#8e44ad; color:white;" onclick="verifyCertificateById()">🔎 সার্টিফিকেট আইডি যাচাই</button>
                <button class="admin-action-btn super-only" style="background:#e74c3c; color:white;" onclick="resetAllData()">🗑️ সব ডেটা রিসেট</button>
            </div>
        </div>
    </div>

    <script>
        // আপনার URL বসান:
        const SCRIPT_URL = "https://script.google.com/macros/s/AKfycbznLIlUsb4e5tH-Q6YI_WdP9gMELYafkLmn14ISL6fwsm3U4jPCZRr_X3aJfaXqstDZsw/exec";
        // ===== CONFIG =====
        const ADMIN_PASSWORD = "2004";           // মডারেটর পাসওয়ার্ড (সীমিত এক্সেস)
        const SUPER_ADMIN_PASSWORD = "260426";    // সুপার অ্যাডমিন পাসওয়ার্ড (পূর্ণ এক্সেস) — চাইলে বদলে নিন
        let currentAdminRole = null; // 'super' | 'moderator' | null

        // ===== STATE =====
        let isEntryVerified = false;
        let isCompetitionActive = false;
        let isPracticeMode = false;
        let currentStep = 1,
            currentIdx = 0,
            correctCount = 0,
            wrongCount = 0,
            totalTime = 180, // সময় ১৮০ সেকেন্ড করা হয়েছে
            timer;
        let playerName = "",
            playerMobile = "",
            entryCode = "";
        let stepQuestions = [];
        let quizActive = false;
        let startTime = null;

        // ===== LIFELINE STATE =====
        let state5050 = false,
            stateTime = false,
            stateAnswer = false,
            statePoll = false,
            stateGuard = false;
        let isGuardActiveNow = false;

        // ===== MYSTERY BOX STATE =====
        let streakCount = 0;
        let doubleScoreActive = false;
        let skipQuestionActive = false;
        let hintActive = false;
        let hintUsedForCurrentQ = false;

        const mysteryRewards = [
            "life_restore", 
            "guard", 
            "time_20", 
            "time_30", 
            "time_50", 
            "time_60", 
            "free_score", 
            "double_score",
            "skip_question",
            "extra_time",
            "hint",
            "bonus"
        ];

        // ===== SHARED DATA =====
        function getParticipants() {
            return JSON.parse(localStorage.getItem('mp_participants') || '[]');
        }

        function setParticipants(data) {
            localStorage.setItem('mp_participants', JSON.stringify(data));
        }

        function getScores() {
            return JSON.parse(localStorage.getItem('mp_scores') || '{}');
        }

        function setScores(data) {
            localStorage.setItem('mp_scores', JSON.stringify(data));
        }

        function getActiveCodes() {
            return JSON.parse(localStorage.getItem('mp_activeCodes') || '[]');
        }

        function setActiveCodes(data) {
            localStorage.setItem('mp_activeCodes', JSON.stringify(data));
        }

        function getCompetitionStatus() {
            return localStorage.getItem('mp_competitionActive') === 'true';
        }

        function setCompetitionStatus(status) {
            localStorage.setItem('mp_competitionActive', status ? 'true' : 'false');
        }

        // ===== 🏅 Hall of Fame দৃশ্যমানতা (ডিফল্টে লুকানো, কুইজ/প্রতিযোগিতা শেষ হলে বা অ্যাডমিন টগল করলে দেখাবে) =====
        function getHallOfFameVisible() {
            return localStorage.getItem('mp_hallOfFameVisible') === 'true';
        }

        function setHallOfFameVisible(visible) {
            localStorage.setItem('mp_hallOfFameVisible', visible ? 'true' : 'false');
            updateHallOfFameButtonVisibility();
        }

        function updateHallOfFameButtonVisibility() {
            const btn = document.getElementById('hallOfFameBtn');
            if (btn) btn.style.display = getHallOfFameVisible() ? 'block' : 'none';
        }

        // ===== অ্যাডমিন কন্ট্রোলড কুইজ টাইমার (সেকেন্ডে) =====
        function getQuizDuration() {
            const v = parseInt(localStorage.getItem('mp_quizDuration'), 10);
            return (!isNaN(v) && v > 0) ? v : 3600; // ডিফল্ট ৬০ মিনিট
        }

        function setQuizDuration(seconds) {
            localStorage.setItem('mp_quizDuration', String(seconds));
        }

        // ===== 📖 উত্তর রিভিউ মোড (অ্যাডমিন অন/অফ) =====
        function getAnswerReviewEnabled() {
            return localStorage.getItem('mp_answerReviewEnabled') !== 'false'; // ডিফল্ট: চালু
        }

        function setAnswerReviewEnabled(enabled) {
            localStorage.setItem('mp_answerReviewEnabled', enabled ? 'true' : 'false');
        }

        // ===== ⏱️ অংশগ্রহণকারীর সময় রেকর্ড (মেধা তালিকা/টাই-ব্রেক ও সময়-এনালিটিক্সের জন্য) =====
        function getCompletionTimes() {
            return JSON.parse(localStorage.getItem('mp_completionTimes') || '{}');
        }

        function setCompletionTime(mobile, seconds) {
            const times = getCompletionTimes();
            times[mobile] = seconds;
            localStorage.setItem('mp_completionTimes', JSON.stringify(times));
        }

        // ===== 🎲 লাকি ড্র সেটিংস (অ্যাডমিন কর্তৃক নিয়ন্ত্রিত এলিজিবিলিটি) =====
        function getLuckyDrawMinScore() {
            const v = parseInt(localStorage.getItem('mp_luckyDrawMinScore'), 10);
            return !isNaN(v) ? v : 0;
        }

        function setLuckyDrawMinScore(v) {
            localStorage.setItem('mp_luckyDrawMinScore', String(v));
        }

        // ===== 🎓 সার্টিফিকেট টেমপ্লেট সেটিংস (অ্যাডমিন কাস্টমাইজযোগ্য) =====
        function getCertificateTemplate() {
            return JSON.parse(localStorage.getItem('mp_certTemplate') || '{}');
        }

        function setCertificateTemplate(cfg) {
            localStorage.setItem('mp_certTemplate', JSON.stringify(cfg));
        }

        function saveCertTemplateSettings() {
            const color = document.getElementById('certColorInput').value;
            const logo = document.getElementById('certLogoInput').value.trim();
            setCertificateTemplate({ color, logoEmoji: logo || '🕌' });
            alert('✅ সার্টিফিকেট টেমপ্লেট সেটিংস সেভ হয়েছে। পরবর্তী সব সার্টিফিকেটে প্রয়োগ হবে।');
        }

        // ===== 🎓 ইস্যুকৃত সার্টিফিকেট রেকর্ড (আইডি দিয়ে পরে যাচাইয়ের জন্য) =====
        function getCertificateRecords() {
            return JSON.parse(localStorage.getItem('mp_certificates') || '{}');
        }

        function saveCertificateRecord(certId, data) {
            const records = getCertificateRecords();
            records[certId] = data;
            localStorage.setItem('mp_certificates', JSON.stringify(records));
        }

        function generateCertId() {
            return 'GC-' + Date.now().toString(36).toUpperCase() + '-' + Math.random().toString(36).slice(2, 7).toUpperCase();
        }

        // ===== 🔢 প্রতিটি সার্টিফিকেটের জন্য ক্রমিক, মানুষ-পঠনযোগ্য সিরিয়াল নম্বর (প্রতিটি একেবারে ইউনিক) =====
        function getNextCertSerial() {
            let counter = parseInt(localStorage.getItem('mp_certSerialCounter'), 10);
            if (isNaN(counter)) counter = 0;
            counter++;
            localStorage.setItem('mp_certSerialCounter', String(counter));
            const year = new Date().getFullYear();
            return `GC-${year}-${String(counter).padStart(4, '0')}`;
        }

        // ===== 🏅 XP / Level / Badge / Daily Streak (লোকাল, ডিভাইস-ভিত্তিক) =====
        const BADGE_DEFS = {
            first_quiz: { label: '🎉 প্রথম কুইজ সম্পন্ন', desc: 'প্রথমবার কুইজ সম্পন্ন করেছেন' },
            perfect_score: { label: '💯 পারফেক্ট স্কোর', desc: 'কোনো ভুল ছাড়া উত্তর দিয়েছেন' },
            high_scorer: { label: '🌟 হাই স্কোরার', desc: '৮০+ স্কোর অর্জন করেছেন' },
            mystery_master: { label: '🎁 মিস্টারি মাস্টার', desc: 'একই কুইজে ৩টি মিস্টারি বক্স খুলেছেন' },
            streak_3: { label: '🔥 ৩ দিনের ধারা', desc: 'টানা ৩ দিন অংশগ্রহণ/অনুশীলন করেছেন' },
            streak_7: { label: '🔥🔥 ৭ দিনের ধারা', desc: 'টানা ৭ দিন অংশগ্রহণ/অনুশীলন করেছেন' }
        };

        function getPlayerProgressKey(mobile) {
            return mobile && mobile.trim() ? mobile.trim() : 'guest_device';
        }

        function getAllPlayerProgress() {
            return JSON.parse(localStorage.getItem('mp_playerProgress') || '{}');
        }

        function getPlayerProgress(mobile) {
            const all = getAllPlayerProgress();
            const key = getPlayerProgressKey(mobile);
            return all[key] || { xp: 0, level: 1, badges: [], lastPlayDate: null, streak: 0 };
        }

        function savePlayerProgress(mobile, progress) {
            const all = getAllPlayerProgress();
            all[getPlayerProgressKey(mobile)] = progress;
            localStorage.setItem('mp_playerProgress', JSON.stringify(all));
        }

        function todayDateString() {
            return new Date().toISOString().slice(0, 10);
        }

        function updateAchievements(mobile, finalScore, totalQ, wrongCountVal) {
            const progress = getPlayerProgress(mobile);
            const newBadges = [];
            const isFirst = progress.xp === 0 && progress.badges.length === 0;

            // XP: স্কোরের সমান XP
            progress.xp += finalScore;
            const newLevel = Math.floor(progress.xp / 500) + 1;
            const leveledUp = newLevel > progress.level;
            progress.level = newLevel;

            // দৈনিক ধারা (streak)
            const today = todayDateString();
            if (progress.lastPlayDate !== today) {
                const yesterday = new Date(Date.now() - 86400000).toISOString().slice(0, 10);
                progress.streak = (progress.lastPlayDate === yesterday) ? progress.streak + 1 : 1;
                progress.lastPlayDate = today;
            }

            // ব্যাজ নির্ধারণ
            const earn = (key) => { if (!progress.badges.includes(key)) { progress.badges.push(key); newBadges.push(key); } };
            if (isFirst) earn('first_quiz');
            if (wrongCountVal === 0) earn('perfect_score');
            if (finalScore >= Math.round(totalQ * 0.8)) earn('high_scorer');
            if (mysteryBoxesOpenedThisSession >= 3) earn('mystery_master');
            if (progress.streak >= 3) earn('streak_3');
            if (progress.streak >= 7) earn('streak_7');

            savePlayerProgress(mobile, progress);
            return { progress, newBadges, leveledUp };
        }

        // ===== প্রতিযোগিতার সময়সূচি (শুরু/শেষ) — হোমপেজ কাউন্টডাউনের জন্য =====
        function getCompetitionSchedule() {
            try {
                return JSON.parse(localStorage.getItem('mp_schedule') || 'null');
            } catch (e) { return null; }
        }

        function setCompetitionSchedule(startISO, endISO) {
            localStorage.setItem('mp_schedule', JSON.stringify({ start: startISO, end: endISO }));
        }

        function clearCompetitionSchedule() {
            localStorage.removeItem('mp_schedule');
        }

        // ===== সতর্কতা / চিটিং লগ =====
        function getCheatLogs() {
            return JSON.parse(localStorage.getItem('mp_cheatLogs') || '[]');
        }

        function addCheatLog(reason) {
            const logs = getCheatLogs();
            logs.push({
                name: playerName || '(নিবন্ধনের আগে)',
                mobile: playerMobile || '-',
                reason: reason,
                time: new Date().toLocaleString('bn-BD')
            });
            localStorage.setItem('mp_cheatLogs', JSON.stringify(logs));
        }

        function showCheatLogs() {
            const logs = getCheatLogs();
            if (logs.length === 0) {
                alert('✅ এখনো কোনো সতর্কতা/চিটিং লগ রেকর্ড হয়নি।');
                return;
            }
            const text = logs.slice(-50).map((l, i) =>
                `${i + 1}. ${l.name} (${l.mobile})\n   কারণ: ${l.reason}\n   সময়: ${l.time}`
            ).join('\n\n');
            alert('🕵️ সাম্প্রতিক সতর্কতা লগ (সর্বশেষ ৫০টি):\n\n' + text);
        }

        // ===== 📉 সবচেয়ে বেশি ভুল হওয়া প্রশ্নের রিপোর্ট =====
        function showWrongQuestionsReport() {
            const stats = getQuestionStats();
            const entries = Object.entries(stats).map(([q, s]) => {
                const total = s.correct + s.wrong;
                const wrongRate = total > 0 ? Math.round((s.wrong / total) * 100) : 0;
                return { q, correct: s.correct, wrong: s.wrong, total, wrongRate };
            });

            if (entries.length === 0) {
                alert('📉 এখনো কোনো প্রশ্নের উত্তর দেওয়া হয়নি, তাই রিপোর্ট তৈরি করা যাচ্ছে না।');
                return;
            }

            // যথেষ্ট নমুনা (কমপক্ষে ২ বার উত্তর দেওয়া) আছে এমন প্রশ্ন আগে, বাকিগুলো পরে
            const withEnoughData = entries.filter(e => e.total >= 2).sort((a, b) => b.wrongRate - a.wrongRate || b.wrong - a.wrong);
            const lowData = entries.filter(e => e.total < 2).sort((a, b) => b.wrong - a.wrong);
            const sorted = [...withEnoughData, ...lowData].slice(0, 20);

            const text = sorted.map((e, i) => {
                const shortQ = e.q.length > 55 ? e.q.slice(0, 55) + '…' : e.q;
                return `${i + 1}. ${shortQ}\n   ✅ সঠিক: ${e.correct} | ❌ ভুল: ${e.wrong} | ভুলের হার: ${e.wrongRate}%${e.total < 2 ? ' (নমুনা কম)' : ''}`;
            }).join('\n\n');

            alert('📉 সবচেয়ে বেশি ভুল হওয়া প্রশ্ন (টপ ২০, ভুলের হার অনুযায়ী):\n\nমোট উত্তর দেওয়া হয়েছে এমন প্রশ্ন: ' + entries.length + 'টি\n\n' + text +
                '\n\n💡 ইঙ্গিত: ভুলের হার খুব বেশি (৭০%+) হলে প্রশ্নটা হয়তো খুব কঠিন বা অপশনে/উত্তরে ভুল আছে কিনা যাচাই করুন।');
        }

        // ===== 📊 উন্নত এনালিটিক্স (ক্যাটাগরি পারফরম্যান্স + সময় এনালিসিস + প্লেয়ার একটিভিটি) =====
        function showAdvancedAnalytics() {
            // ১) ক্যাটাগরি পারফরম্যান্স (প্রশ্নের কঠিনতা-স্তর অনুযায়ী সামগ্রিক সঠিক/ভুলের হার)
            const stats = getQuestionStats();
            const pool = getActiveQuestionPool();
            const diffMap = {};
            pool.forEach(q => { diffMap[q.q] = q.diff; });

            const catTotals = { easy: { c: 0, w: 0 }, medium: { c: 0, w: 0 }, hard: { c: 0, w: 0 }, practice: { c: 0, w: 0 } };
            Object.entries(stats).forEach(([q, s]) => {
                const d = diffMap[q] || 'medium';
                if (!catTotals[d]) catTotals[d] = { c: 0, w: 0 };
                catTotals[d].c += s.correct;
                catTotals[d].w += s.wrong;
            });

            const catLabels = { easy: '🟢 সহজ', medium: '🟡 মধ্যম', hard: '🔴 কঠিন', practice: '📚 প্র্যাকটিস' };
            let catText = '';
            Object.keys(catLabels).forEach(k => {
                const t = catTotals[k];
                const total = t.c + t.w;
                if (total > 0) {
                    const accuracy = Math.round((t.c / total) * 100);
                    catText += `${catLabels[k]}: সঠিকতার হার ${accuracy}% (✅ ${t.c} | ❌ ${t.w}, মোট ${total} উত্তর)\n`;
                }
            });
            if (!catText) catText = 'এখনো কোনো ক্যাটাগরির ডেটা নেই।\n';

            // ২) সময় এনালিসিস (প্রতিযোগিতায় অংশ নেওয়া প্রকৃত অংশগ্রহণকারীদের সময়)
            const times = Object.values(getCompletionTimes());
            let timeText = 'এখনো কোনো সম্পন্ন কুইজের সময়ের তথ্য নেই।';
            if (times.length > 0) {
                const avgSec = Math.round(times.reduce((a, b) => a + b, 0) / times.length);
                const minSec = Math.min(...times);
                const maxSec = Math.max(...times);
                const fmt = s => `${Math.floor(s / 60)} মিনিট ${s % 60} সেকেন্ড`;
                timeText = `গড় সময়: ${fmt(avgSec)}\nদ্রুততম: ${fmt(minSec)}\nধীরতম: ${fmt(maxSec)}\nমোট সম্পন্ন কুইজ: ${times.length}টি`;
            }

            // ৩) প্লেয়ার একটিভিটি ড্যাশবোর্ড
            const participants = getParticipants();
            const scores = getScores();
            const activeCount = participants.filter(p => scores[p.mobile] > 0).length;
            const completionRate = participants.length > 0 ? Math.round((activeCount / participants.length) * 100) : 0;
            const cheatLogCount = getCheatLogs().length;

            const activityText = `মোট নিবন্ধিত অংশগ্রহণকারী: ${participants.length}জন\n` +
                `কুইজ সম্পন্নকারী: ${activeCount}জন (${completionRate}% সম্পন্নতার হার)\n` +
                `মোট সতর্কতা/চিটিং লগ: ${cheatLogCount}টি`;

            alert('📊 উন্নত এনালিটিক্স ড্যাশবোর্ড\n\n' +
                '📚 ক্যাটাগরি পারফরম্যান্স (সামগ্রিক):\n' + catText + '\n' +
                '⏱️ সময় এনালিসিস:\n' + timeText + '\n\n' +
                '👥 প্লেয়ার একটিভিটি:\n' + activityText);
        }

        // ===== 🖨️ প্রশ্ন প্রিন্ট / PDF মোড (ব্রাউজারের প্রিন্ট ডায়ালগ থেকে "Save as PDF" করা যাবে) =====
        function printQuestionBank() {
            const pool = getActiveQuestionPool();
            if (pool.length === 0) {
                alert('⚠️ কোনো সক্রিয় প্রশ্ন পাওয়া যায়নি।');
                return;
            }

            const labels = { easy: 'সহজ', medium: 'মধ্যম', hard: 'কঠিন' };
            const groups = { easy: [], medium: [], hard: [] };
            pool.forEach(q => {
                const d = groups[q.diff] ? q.diff : 'medium';
                groups[d].push(q);
            });

            let bodyHtml = '';
            let counter = 1;
            ['easy', 'medium', 'hard'].forEach(diff => {
                if (groups[diff].length === 0) return;
                bodyHtml += `<h2>${labels[diff]} (${groups[diff].length}টি)</h2>`;
                groups[diff].forEach(q => {
                    const opts = ['a', 'b', 'c', 'd'];
                    bodyHtml += `<div class="q-block"><p class="q-text">${counter}. ${escapeHtml(q.q)}</p><ol type="a" class="opts">`;
                    opts.forEach(k => {
                        const isCorrect = k === q.ans;
                        bodyHtml += `<li${isCorrect ? ' class="correct-opt"' : ''}>${escapeHtml(q[k])}${isCorrect ? ' ✅' : ''}</li>`;
                    });
                    bodyHtml += '</ol></div>';
                    counter++;
                });
            });

            const printWin = window.open('', '_blank');
            if (!printWin) {
                alert('⚠️ পপ-আপ ব্লক করা আছে। ব্রাউজারে এই সাইটের জন্য পপ-আপ অনুমতি দিন এবং আবার চেষ্টা করুন।');
                return;
            }

            printWin.document.write(`
                <!DOCTYPE html>
                <html lang="bn">
                <head>
                <meta charset="UTF-8">
                <title>গাউসিয়া কমিটি - প্রশ্নব্যাংক (প্রিন্ট)</title>
                <style>
                    body { font-family: 'Segoe UI', 'SolaimanLipi', sans-serif; padding: 30px; color: #222; }
                    h1 { text-align:center; color:#18661F; margin-bottom:2px; }
                    .sub { text-align:center; color:#666; margin-bottom:20px; font-size:13px; }
                    h2 { color:#1e3c72; border-bottom:2px solid #1e3c72; padding-bottom:4px; margin-top:28px; }
                    .q-block { margin-bottom:14px; page-break-inside: avoid; }
                    .q-text { font-weight:bold; margin-bottom:4px; }
                    .opts { margin:0 0 0 20px; padding:0; }
                    .opts li { margin-bottom:2px; }
                    .correct-opt { color:#18661F; font-weight:bold; }
                    @media print {
                        body { padding: 10px; }
                    }
                </style>
                </head>
                <body>
                    <h1>গাউসিয়া কমিটি বাংলাদেশ — কুইজ কম্পিটিশন ২০২৬</h1>
                    <div class="sub">প্রশ্নব্যাংক (সঠিক উত্তরসহ) — মোট ${pool.length}টি প্রশ্ন — শুধুমাত্র অ্যাডমিন/যাচাইয়ের জন্য</div>
                    ${bodyHtml}
                </body>
                </html>
            `);
            printWin.document.close();
            printWin.focus();
            setTimeout(() => printWin.print(), 400);
        }

        // ===== 📖 কুইজ রিভিউ (নিজের উত্তরসহ সব প্রশ্ন দেখা ও PDF ডাউনলোড) =====
        function showAnswerReview() {
            if (!answerLog || answerLog.length === 0) {
                alert('⚠️ এই সেশনের কোনো উত্তরের তথ্য পাওয়া যায়নি।');
                return;
            }

            const optLabel = { a: 'ক', b: 'খ', c: 'গ', d: 'ঘ' };
            let bodyHtml = '';
            answerLog.forEach((item, i) => {
                const rowColor = item.correct ? '#e8f5e9' : '#fdecea';
                const yourAnsText = item[item.selected];
                const correctAnsText = item[item.ans];
                bodyHtml += `<div class="q-block" style="background:${rowColor};">
                    <p class="q-text">${i + 1}. ${escapeHtml(item.q)}</p>
                    <p style="margin:2px 0;">আপনার উত্তর: <b>${optLabel[item.selected]}) ${escapeHtml(yourAnsText)}</b> ${item.correct ? '✅' : '❌'}${item.viaLifeline ? ' (লাইফলাইন ব্যবহার করে)' : ''}</p>
                    ${!item.correct ? `<p style="margin:2px 0; color:#18661F;">সঠিক উত্তর: <b>${optLabel[item.ans]}) ${escapeHtml(correctAnsText)}</b></p>` : ''}
                </div>`;
            });

            const correctN = answerLog.filter(a => a.correct).length;
            const wrongN = answerLog.length - correctN;

            const reviewWin = window.open('', '_blank');
            if (!reviewWin) {
                alert('⚠️ পপ-আপ ব্লক করা আছে। ব্রাউজারে এই সাইটের জন্য পপ-আপ অনুমতি দিন এবং আবার চেষ্টা করুন।');
                return;
            }

            reviewWin.document.write(`
                <!DOCTYPE html>
                <html lang="bn">
                <head>
                <meta charset="UTF-8">
                <title>কুইজ রিভিউ - ${escapeHtml(playerName || 'অতিথি')}</title>
                <style>
                    body { font-family: 'Segoe UI', 'SolaimanLipi', sans-serif; padding: 30px; color: #222; }
                    h1 { text-align:center; color:#18661F; margin-bottom:2px; }
                    .sub { text-align:center; color:#666; margin-bottom:20px; font-size:13px; }
                    .q-block { margin-bottom:10px; padding:10px; border-radius:8px; page-break-inside: avoid; }
                    .q-text { font-weight:bold; margin-bottom:4px; }
                    @media print { body { padding: 10px; } }
                </style>
                </head>
                <body>
                    <h1>গাউসিয়া কমিটি বাংলাদেশ — কুইজ রিভিউ</h1>
                    <div class="sub">অংশগ্রহণকারী: ${escapeHtml(playerName || 'অতিথি')} | সঠিক: ${correctN} | ভুল: ${wrongN} | মোট: ${answerLog.length}</div>
                    ${bodyHtml}
                </body>
                </html>
            `);
            reviewWin.document.close();
            reviewWin.focus();
        }

        // ===== 🌐 মাল্টি-ডিভাইস সিঙ্ক ব্যাকএন্ড (Google Apps Script) =====
        // apps-script-backend.gs ডিপ্লয় করা থাকলেই এটা কাজ করবে; না থাকলে সব ফাংশন
        // স্বয়ংক্রিয়ভাবে লোকাল (এই ডিভাইস-শুধু) মোডে ফিরে যাবে — কিছুই ভাঙবে না।
        function isBackendConfigured() {
            return !!SCRIPT_URL && !SCRIPT_URL.includes('YOUR_SCRIPT_ID');
        }

        async function callBackend(params) {
            if (!isBackendConfigured()) return null;
            try {
                const query = new URLSearchParams(params).toString();
                const res = await fetch(SCRIPT_URL + '?' + query, { method: 'GET' });
                if (!res.ok) throw new Error('HTTP ' + res.status);
                const json = await res.json();
                return json;
            } catch (err) {
                console.warn('⚠️ ব্যাকএন্ড সংযোগ ব্যর্থ, লোকাল মোডে চলছে:', err);
                return null;
            }
        }

        // ===== ২৫০টি প্রশ্ন (সহজ ১০০, মধ্যম ৭৫, কঠিন ৭৫) =====
        const easyQuestions = [
            { q: "ঈমান শব্দের অর্থ কী?", a: "বিশ্বাস", b: "অবিশ্বাস", c: "সন্দেহ", d: "ভয়", ans: "a" },
            { q: "ইসলামের মৌলিক স্তম্ভ কয়টি?", a: "৩", b: "৪", c: "৫", d: "৬", ans: "c" },
            { q: "ফজরের নামাজ কয় রাকাত?", a: "২", b: "৩", c: "৪", d: "১", ans: "a" },
            { q: "নবীজির পিতার নাম কী?", a: "আব্দুল্লাহ", b: "আবু তালিব", c: "হামজা", d: "আব্বাস", ans: "a" },
            { q: "কুরআনের প্রথম সূরা কোনটি?", a: "ফাতিহা", b: "বাকারা", c: "ইখলাস", d: "নাস", ans: "a" },
            { q: "জান্নাতে কি প্রবাহিত হয়?", a: "নদী", b: "আগুন", c: "ধোঁয়া", d: "পাথর", ans: "a" },
            { q: "ফেরেশতা কী দিয়ে তৈরি?", a: "আলো", b: "মাটি", c: "আগুন", d: "পানি", ans: "a" },
            { q: "কুরআনে কয়টি সূরা আছে?", a: "১১৪", b: "১১০", c: "১২০", d: "১১৬", ans: "a" },
            { q: "সবচেয়ে বড় সূরা কোনটি?", a: "বাকারা", b: "ইখলাস", c: "ফাতিহা", d: "নাস", ans: "a" },
            { q: "নবীজি কোথায় জন্মগ্রহণ করেন?", a: "মক্কা", b: "মদিনা", c: "তায়েফ", d: "বাগদাদ", ans: "a" },
            { q: "আসমানী কিতাব কয়টি?", a: "১০৪", b: "৪", c: "১০০", d: "১০", ans: "a" },
            { q: "প্রথম খলিফা কে?", a: "আবু বকর", b: "উমর", c: "উসমান", d: "আলী", ans: "a" },
            { q: "যাকাত কত বছর পর দিতে হয়?", a: "১", b: "৬ মাস", c: "২", d: "৫", ans: "a" },
            { q: "জান্নাতের দরজা কয়টি?", a: "৮", b: "৪", c: "৭", d: "১০", ans: "a" },
            { q: "হজ ইসলামের কততম রুকন?", a: "৫ম", b: "৩য়", c: "৪র্থ", d: "২য়", ans: "a" },
            { q: "বদর যুদ্ধ কত হিজরিতে?", a: "২য়", b: "১ম", c: "৩য়", d: "৪র্থ", ans: "a" },
            { q: "দ্বিতীয় খলিফা কে?", a: "উমর", b: "আলী", c: "উসমান", d: "বিলাল", ans: "a" },
            { q: "আল্লাহর ঘর叫什么?", a: "কাবা", b: "মসজিদে নববী", c: "আকসা", d: "বায়তুল মামুর", ans: "a" },
            { q: "নামাজের চাবি কী?", a: "পবিত্রতা", b: "হজ", c: "যাকাত", d: "সালাম", ans: "a" },
            { q: "মেরাজ কোন মাসে?", a: "রজব", b: "রমজান", c: "শাওয়াল", d: "মুহাররম", ans: "a" },
            { q: "তওরাত কার ওপর নাযিল?", a: "মুসা", b: "ঈসা", c: "দাউদ", d: "মুহাম্মদ", ans: "a" },
            { q: "ফেরাউন কোন নবীর শত্রু?", a: "মুসা", b: "নুহ", c: "ঈসা", d: "ইব্রাহিম", ans: "a" },
            { q: "বৃষ্টির দায়িত্ব কোন ফেরেশতার?", a: "মিকাইল", b: "জিবরাইল", c: "আজরাইল", d: "ইসরাফিল", ans: "a" },
            { q: "উম্মুল কুরআন কোন সূরা?", a: "ফাতিহা", b: "ইখলাস", c: "ইয়াসিন", d: "বাকারা", ans: "a" },
            { q: "প্রথম আযান কে দেন?", a: "বিলাল", b: "আবু বকর", c: "আলী", d: "উমর", ans: "a" },
            { q: "কুরআন কোন রাতে নাযিল হয়?", a: "লাইলাতুল কদর", b: "শবে বরাত", c: "মেরাজ", d: "আরাফাত", ans: "a" },
            { q: "হজের প্রধান কাজ কী?", a: "আরাফাতে অবস্থান", b: "সাফা-মারওয়া", c: "মিনায় থাকা", d: "পাথর মারা", ans: "a" },
            { q: "হিজরি সাল শুরু করেন কে?", a: "উমর", b: "আবু বকর", c: "উসমান", d: "আলী", ans: "a" },
            { q: "সাইয়্যিদুল মুরসালিন কে?", a: "মুহাম্মদ", b: "আদম", c: "ইব্রাহিম", d: "নুহ", ans: "a" },
            { q: "কিয়ামতে হিসাব নেবেন কে?", a: "আল্লাহ", b: "নবীগণ", c: "ফেরেশতারা", d: "ওলীগণ", ans: "a" },
            { q: "সবচেয়ে ছোট সূরা কোনটি?", a: "কাউসার", b: "ইখলাস", c: "নাস", d: "ফালাক", ans: "a" },
            { q: "বদর যুদ্ধে শহীদ কতজন?", a: "১৪", b: "১২", c: "৮", d: "১৬", ans: "a" },
            { q: "আমলনামা লেখেন কে?", a: "কিরামান কাতিবিন", b: "মুনকার নাকির", c: "জিবরাইল", d: "মিকাইল", ans: "a" },
            { q: "ইসলামের প্রথম যুদ্ধ?", a: "বদর", b: "ওহুদ", c: "খন্দক", d: "খায়বার", ans: "a" },
            { q: "নবীজি কোথায় হিজরত করেন?", a: "ইয়াসরিব", b: "কুফা", c: "বাগদাদ", d: "দামেস্ক", ans: "a" },
            { q: "হাশরে কার সুপারিশ?", a: "মুহাম্মদ", b: "পিতা-মাতা", c: "ফেরেশতা", d: "সাহাবীগণ", ans: "a" },
            { q: "মক্কা বিজয় কত হিজরিতে?", a: "৮", b: "৬", c: "১০", d: "৫", ans: "a" },
            { q: "প্রথম মহিলা শহীদ কে?", a: "সুমাইয়া", b: "খাদিজা", c: "আয়েশা", d: "ফাতিমা", ans: "a" },
            { q: "হাদীসের বর্ণনাকারী পরম্পরা?", a: "সনদ", b: "মতন", c: "রাবী", d: "সূচী", ans: "a" },
            { q: "যাকাতের নিসাব কী?", a: "৭.৫ তোলা স্বর্ণ", b: "৫ তোলা", c: "১০ তোলা", d: "৩ তোলা", ans: "a" },
            { q: "পবিত্র কুরআনে মোট কয়টি পারা?", a: "৩০", b: "২৮", c: "৩২", d: "২৫", ans: "a" },
            { q: "সূরা ইখলাস কয়টি আয়াত?", a: "৪", b: "৫", c: "৩", d: "৬", ans: "a" },
            { q: "নবীজির মাতার নাম কী?", a: "আমিনা", b: "হালিমা", c: "খাদিজা", d: "ফাতিমা", ans: "a" },
            { q: "ওহুদ যুদ্ধ কত হিজরিতে?", a: "৩", b: "২", c: "৪", d: "৫", ans: "a" },
            { q: "খন্দক যুদ্ধ অন্যভাবে কী নামে পরিচিত?", a: "আহযাব", b: "বদর", c: "হুনাইন", d: "তাবুক", ans: "a" },
            { q: "হযরত ইউসুফ (আ.)-এর উপাধি কী?", a: "আহসানুল কাসাস", b: "খলিলুল্লাহ", c: "কালিমুল্লাহ", d: "রুহুল্লাহ", ans: "a" },
            { q: "মহররম মাসের গুরুত্বপূর্ণ দিন কোনটি?", a: "আশুরা", b: "শবে বরাত", c: "লাইলাতুল কদর", d: "ঈদ", ans: "a" },
            { q: "হযরত দাউদ (আ.)-এর কিতাবের নাম কী?", a: "যাবুর", b: "তওরাত", c: "ইঞ্জিল", d: "কুরআন", ans: "a" },
            { q: "ইসলামের প্রথম শহীদ কে?", a: "হযরত ইয়াসির", b: "হযরত সুমাইয়া", c: "হযরত বিলাল", d: "হযরত আবু বকর", ans: "a" },
            { q: "কুরআনের আয়াত সংখ্যা কত?", a: "৬৬৬৬", b: "৬২৩৬", c: "৬০০০", d: "৬৫০০", ans: "a" },
            { q: "পবিত্র মক্কার গুরুত্বপূর্ণ পাহাড় কোনটি?", a: "সাফা-মারওয়া", b: "উহুদ", c: "সিনাই", d: "জাবালুন নূর", ans: "a" },
            { q: "হযরত মুহাম্মদ (দ.)-এর জনক কে?", a: "আব্দুল্লাহ", b: "আবু তালিব", c: "আব্দুল মুত্তালিব", d: "হামজা", ans: "a" },
            { q: "নামাজের কয়টি রাকাত সুন্নত?", a: "১২", b: "১০", c: "১৪", d: "৮", ans: "a" },
            { q: "যাকাত কাদের দেওয়া যায় না?", a: "ধনী ব্যক্তিকে", b: "গরিবকে", c: "মিসকিনকে", d: "ঋণগ্রস্তকে", ans: "a" },
            { q: "হজের সময় কয়টি পাথর মারা হয়?", a: "৭০", b: "৪৯", c: "৩৫", d: "৫৬", ans: "a" },
            { q: "রোজার ফরজ কয়টি?", a: "৩", b: "৪", c: "৫", d: "২", ans: "a" },
            { q: "কুরআনের বৃহত্তম সূরা?", a: "সূরা বাকারা", b: "সূরা ইমরান", c: "সূরা নিসা", d: "সূরা মায়িদা", ans: "a" },
            { q: "ছোট সূরা কাউসারের আয়াত সংখ্যা?", a: "৩", b: "৪", c: "৫", d: "৬", ans: "a" },
            { q: "নবীজি কত বছর বয়সে নবুয়ত পান?", a: "৪০", b: "৩৫", c: "৪৫", d: "৫০", ans: "a" },
            { q: "হিজরত কত সালে ঘটে?", a: "৬২২ খ্রি.", b: "৬১০ খ্রি.", c: "৬৩০ খ্রি.", d: "৬০০ খ্রি.", ans: "a" },
            { q: "মসজিদে নববী কোথায় অবস্থিত?", a: "মদিনা", b: "মক্কা", c: "কুফা", d: "বাগদাদ", ans: "a" },
            { q: "কুরআনের হৃদপিণ্ড কোন সূরা?", a: "সূরা ইয়াসিন", b: "সূরা রহমান", c: "সূরা ফাতিহা", d: "সূরা বাকারা", ans: "a" },
            { q: "আরকানুল ইসলাম কী?", a: "ইসলামের স্তম্ভ", b: "ঈমানের স্তম্ভ", c: "নামাজের স্তম্ভ", d: "হজের স্তম্ভ", ans: "a" },
            { q: "হযরত আবু বকর (রা.) কত বছর খিলাফত করেন?", a: "২ বছর", b: "৪ বছর", c: "৫ বছর", d: "৩ বছর", ans: "a" },
            { q: "হযরত উমর (রা.) কত বছর খিলাফত করেন?", a: "১০ বছর", b: "১২ বছর", c: "৮ বছর", d: "১৫ বছর", ans: "a" },
            { q: "হযরত উসমান (রা.) কত বছর খিলাফত করেন?", a: "১২ বছর", b: "১০ বছর", c: "১৫ বছর", d: "৮ বছর", ans: "a" },
            { q: "হযরত আলী (রা.) কত বছর খিলাফত করেন?", a: "৫ বছর", b: "৪ বছর", c: "৬ বছর", d: "৩ বছর", ans: "a" },
            { q: "আল্লাহর ৯৯ নামের মধ্যে কোনটি সর্বশ্রেষ্ঠ?", a: "আল্লাহ", b: "রহমান", c: "রহিম", d: "মালিক", ans: "a" },
            { q: "আসমাউল হুসনা কাকে বলে?", a: "আল্লাহর সুন্দর নাম", b: "নবীজির নাম", c: "ফেরেশতার নাম", d: "সাহাবীগণের নাম", ans: "a" },
            { q: "সালাতুল ইস্তিখারা কী?", a: "ভালো সিদ্ধান্তের নামাজ", b: "শুকরিয়া নামাজ", c: "তওবা নামাজ", d: "হাজতের নামাজ", ans: "a" },
            { q: "ওযু কয়টি ফরজ?", a: "৪", b: "৩", c: "৫", d: "৬", ans: "a" },
            { q: "গোসল কয়টি ফরজ?", a: "৩", b: "৪", c: "২", d: "৫", ans: "a" },
            { q: "তায়াম্মুম কয়টি ফরজ?", a: "২", b: "৩", c: "৪", d: "৫", ans: "a" },
            { q: "আযানের কয়টি অংশ?", a: "১৫", b: "১৬", c: "১৭", d: "১৪", ans: "a" },
            { q: "ইকামতের কয়টি অংশ?", a: "১১", b: "১২", c: "১৩", d: "১০", ans: "a" },
            { q: "সিজদায় কয়বার তাকবীর দিতে হয়?", a: "১", b: "২", c: "৩", d: "৪", ans: "a" },
            { q: "রুকুতে কয়বার তাকবীর দিতে হয়?", a: "১", b: "২", c: "৩", d: "৪", ans: "a" },
            { q: "কিয়ামতে সবাই কোথায় জমায়েত হবে?", a: "ময়দানে মাহশর", b: "জান্নাত", c: "জাহান্নাম", d: "আরাফাত", ans: "a" },
            { q: "পুলসিরাত কী?", a: "জান্নাতের সেতু", b: "জাহান্নামের সেতু", c: "নদী", d: "পাহাড়", ans: "a" },
            { q: "ইসলাম শব্দের অর্থ কী?", a: "আত্মসমর্পণ", b: "যুদ্ধ", c: "শান্তি নষ্ট করা", d: "ভয়", ans: "a" },
            { q: "মুসলিম শব্দের অর্থ কী?", a: "আত্মসমর্পণকারী", b: "বিদ্রোহী", c: "সন্দিহান", d: "অবিশ্বাসী", ans: "a" },
            { q: "কুরআন নাযিল হতে কত বছর লেগেছিল?", a: "২৩ বছর", b: "১০ বছর", c: "৪০ বছর", d: "৫ বছর", ans: "a" },
            { q: "নবীজি কত বছর মদিনায় ছিলেন?", a: "১০ বছর", b: "৮ বছর", c: "১৩ বছর", d: "৫ বছর", ans: "a" },
            { q: "নবীজি কত বছর মক্কায় ছিলেন (নবুয়তের পর)?", a: "১৩ বছর", b: "১০ বছর", c: "৮ বছর", d: "৫ বছর", ans: "a" },
            { q: "নবীজির মোট বয়স কত ছিল?", a: "৬৩ বছর", b: "৬০ বছর", c: "৭০ বছর", d: "৫৫ বছর", ans: "a" },
            { q: "ইসলামের প্রথম মসজিদ কোনটি?", a: "মসজিদে কুবা", b: "মসজিদে নববী", c: "মসজিদুল হারাম", d: "মসজিদুল আকসা", ans: "a" },
            { q: "প্রথম কিবলা কোনটি ছিল?", a: "মসজিদুল আকসা", b: "কাবা", c: "মসজিদে নববী", d: "মসজিদে কুবা", ans: "a" },
            { q: "কিবলা পরিবর্তন হয় কোন সূরায় উল্লেখিত?", a: "সূরা বাকারা", b: "সূরা ইমরান", c: "সূরা নিসা", d: "সূরা মায়িদা", ans: "a" },
            { q: "জুমার নামাজ সপ্তাহে কতবার?", a: "১ বার", b: "২ বার", c: "৭ বার", d: "৫ বার", ans: "a" },
            { q: "জুমার নামাজ কয় রাকাত ফরজ?", a: "২", b: "৪", c: "৩", d: "৬", ans: "a" },
            { q: "ঈদের নামাজ বছরে কতবার?", a: "২ বার", b: "১ বার", c: "৩ বার", d: "৪ বার", ans: "a" },
            { q: "তারাবীহ নামাজ কোন মাসে পড়া হয়?", a: "রমজান", b: "শাওয়াল", c: "রজব", d: "শাবান", ans: "a" },
            { q: "সাদাকাতুল ফিতর কখন দিতে হয়?", a: "ঈদের আগে", b: "ঈদের পরে", c: "রমজানের আগে", d: "যেকোনো সময়", ans: "a" },
            { q: "কুরবানির ঈদ অন্য নামে কী পরিচিত?", a: "ঈদুল আযহা", b: "ঈদুল ফিতর", c: "শবে বরাত", d: "লাইলাতুল কদর", ans: "a" },
            { q: "রোজার ঈদ অন্য নামে কী পরিচিত?", a: "ঈদুল ফিতর", b: "ঈদুল আযহা", c: "আশুরা", d: "মেরাজ", ans: "a" },
            { q: "হজের মাস কোনটি?", a: "জিলহজ", b: "রমজান", c: "মুহাররম", d: "রজব", ans: "a" },
            { q: "কাবা ঘর কে নির্মাণ করেন?", a: "ইব্রাহিম ও ইসমাইল (আ.)", b: "মুসা (আ.)", c: "নুহ (আ.)", d: "আদম (আ.)", ans: "a" },
            { q: "সাফা-মারওয়া সাঈ কোন ঘটনার স্মরণে?", a: "হাজেরা (আ.)-এর পানি সন্ধান", b: "ইব্রাহিমের কুরবানি", c: "নুহের কিশতি", d: "মুসার লাঠি", ans: "a" },
            { q: "মিনায় শয়তানকে পাথর মারার রীতি কোন ঘটনার স্মরণে?", a: "ইব্রাহিম (আ.)-এর পরীক্ষা", b: "নুহের প্লাবন", c: "মুসার লাঠি", d: "ইউসুফের স্বপ্ন", ans: "a" },
            { q: "ইসলামের সবচেয়ে বড় উৎসব কোনটি?", a: "ঈদুল ফিতর ও ঈদুল আযহা", b: "শবে বরাত", c: "মেরাজ", d: "আশুরা", ans: "a" }
        ];

        const mediumQuestions = [
            { q: "মুনকার-নাকির কারা?", a: "প্রশ্নকারী ফেরেশতা", b: "আজরাইল", c: "জিবরাইল", d: "মিকাইল", ans: "a" },
            { q: "কবরের আযাব কোন ধরনের?", a: "আত্মিক", b: "শারীরিক", c: "উভয়", d: "নেই", ans: "a" },
            { q: "শাফায়াত কী?", a: "সুপারিশ", b: "শাস্তি", c: "পুরস্কার", d: "হিসাব", ans: "a" },
            { q: "আল্লাহর আরশ কোথায়?", a: "৭ম আসমানে", b: "৬ষ্ঠ আসমানে", c: "৫ম আসমানে", d: "৪র্থ আসমানে", ans: "a" },
            { q: "কুরসি কী?", a: "আল্লাহর সিংহাসন", b: "ফেরেশতার স্থান", c: "জান্নাত", d: "জাহান্নাম", ans: "a" },
            { q: "লাওহে মাহফুজ কী?", a: "সংরক্ষিত ফলক", b: "নামাজের স্থান", c: "হজের স্থান", d: "যাকাতের স্থান", ans: "a" },
            { q: "কালামুল্লাহ কী?", a: "আল্লাহর বাণী", b: "নবীজির কথা", c: "ফেরেশতার কথা", d: "সাহাবীদের কথা", ans: "a" },
            { q: "ইসলামের শেষ নবী কে?", a: "মুহাম্মদ", b: "ঈসা", c: "ইব্রাহিম", d: "মুসা", ans: "a" },
            { q: "আম্বিয়াদের মধ্যে কে প্রথম?", a: "আদম", b: "ইদরিস", c: "নুহ", d: "ইব্রাহিম", ans: "a" },
            { q: "উলুল আজম কয়জন?", a: "৫", b: "৪", c: "৬", d: "৩", ans: "a" },
            { q: "খাতামুন নাবিয়্যিন কাকে বলে?", a: "মুহাম্মদ", b: "ঈসা", c: "ইব্রাহিম", d: "মুসা", ans: "a" },
            { q: "কুরআন কোন ভাষায় নাযিল হয়েছে?", a: "আরবি", b: "ইংরেজি", c: "উর্দু", d: "ফার্সি", ans: "a" },
            { q: "আল্লাহর কোন নাম অর্থ 'দয়ালু'?", a: "রহমান", b: "মালিক", c: "কুদ্দুস", d: "আজিজ", ans: "a" },
            { q: "আল্লাহর কোন নাম অর্থ 'ক্ষমাশীল'?", a: "গফুর", b: "রহিম", c: "ওয়াদুদ", d: "মজিদ", ans: "a" },
            { q: "হযরত জিবরাইল (আ.)-এর অন্য নাম কী?", a: "রুহুল আমিন", b: "রুহুল কুদ্দুস", c: "উভয়", d: "কোনটিই নয়", ans: "a" },
            { q: "ইসলামে কয়টি আসমান?", a: "৭", b: "৫", c: "৩", d: "৯", ans: "a" },
            { q: "কুরআনের সিজদার আয়াত কয়টি?", a: "১৪", b: "১৫", c: "১৬", d: "১৩", ans: "a" },
            { q: "সূরা রহমানে কয়টি আয়াত?", a: "৭৮", b: "৭৫", c: "৮০", d: "৮২", ans: "a" },
            { q: "সূরা ইয়াসিনকে কী বলা হয়?", a: "কুরআনের হৃদয়", b: "কুরআনের মুখ", c: "কুরআনের চোখ", d: "কুরআনের কান", ans: "a" },
            { q: "সূরা ফাতিহার আরেক নাম কী?", a: "উম্মুল কিতাব", b: "উম্মুল কুরআন", c: "উভয়", d: "কোনটিই নয়", ans: "a" },
            { q: "সূরা ইখলাস কিসের সমান?", a: "কুরআনের এক-তৃতীয়াংশ", b: "কুরআনের অর্ধেক", c: "কুরআনের চার-পঞ্চমাংশ", d: "কুরআনের দুই-তৃতীয়াংশ", ans: "a" },
            { q: "ইসলামের পঞ্চম স্তম্ভ কী?", a: "হজ", b: "যাকাত", c: "সাওম", d: "সালাত", ans: "a" },
            { q: "ইসলামের দ্বিতীয় স্তম্ভ কী?", a: "সালাত", b: "শাহাদাহ", c: "যাকাত", d: "সাওম", ans: "a" },
            { q: "ইসলামের প্রথম স্তম্ভ কী?", a: "শাহাদাহ", b: "সালাত", c: "যাকাত", d: "সাওম", ans: "a" },
            { q: "ইসলামের চতুর্থ স্তম্ভ কী?", a: "সাওম", b: "হজ", c: "যাকাত", d: "সালাত", ans: "a" },
            { q: "ইসলামের তৃতীয় স্তম্ভ কী?", a: "যাকাত", b: "সালাত", c: "সাওম", d: "হজ", ans: "a" },
            { q: "শাহাদাহ কীভাবে উচ্চারণ করতে হয়?", a: "লা ইলাহা ইল্লাল্লাহু মুহাম্মাদুর রাসুলুল্লাহ", b: "আল্লাহু আকবার", c: "সুবহানাল্লাহ", d: "আলহামদুলিল্লাহ", ans: "a" },
            { q: "ইসলামের মৌলিক বিশ্বাস কয়টি?", a: "৬", b: "৫", c: "৭", d: "৪", ans: "a" },
            { q: "আল্লাহর প্রতি ঈমানের অর্থ কী?", a: "আল্লাহর অস্তিত্বে বিশ্বাস", b: "আল্লাহর ফেরেশতায় বিশ্বাস", c: "আল্লাহর কিতাবে বিশ্বাস", d: "আল্লাহর রাসূলে বিশ্বাস", ans: "a" },
            { q: "ফেরেশতায় ঈমানের অর্থ কী?", a: "ফেরেশতার অস্তিত্বে বিশ্বাস", b: "ফেরেশতার গুণে বিশ্বাস", c: "ফেরেশতার কাজে বিশ্বাস", d: "উভয়", ans: "a" },
            { q: "আসমানী কিতাবে ঈমানের অর্থ কী?", a: "আল্লাহর কিতাবে বিশ্বাস", b: "কিতাবের বিধানে বিশ্বাস", c: "উভয়", d: "কোনটিই নয়", ans: "a" },
            { q: "রাসূলে ঈমানের অর্থ কী?", a: "আল্লাহর রাসূলে বিশ্বাস", b: "রাসূলের গুণে বিশ্বাস", c: "উভয়", d: "কোনটিই নয়", ans: "a" },
            { q: "আখিরাতে ঈমানের অর্থ কী?", a: "পরকালে বিশ্বাস", b: "মৃত্যুর পর জীবন", c: "হাশর-নশরে বিশ্বাস", d: "উভয়", ans: "a" },
            { q: "তাকদিরে ঈমানের অর্থ কী?", a: "ভাগ্যে বিশ্বাস", b: "আল্লাহর ইচ্ছায় বিশ্বাস", c: "উভয়", d: "কোনটিই নয়", ans: "a" },
            { q: "ইসলামের কোন বিধানটি সবচেয়ে গুরুত্বপূর্ণ?", a: "তাওহিদ", b: "নামাজ", c: "যাকাত", d: "হজ", ans: "a" },
            { q: "শিরক কী?", a: "আল্লাহর সাথে কাউকে শরিক করা", b: "আল্লাহকে অস্বীকার করা", c: "নামাজ না পড়া", d: "যাকাত না দেওয়া", ans: "a" },
            { q: "আল্লাহর কোন গুণটি সবচেয়ে গুরুত্বপূর্ণ?", a: "তাওহিদ", b: "রহমান", c: "রহিম", d: "মালিক", ans: "a" },
            { q: "আল্লাহর কয়টি নামে প্রতিদান পাওয়া যায়?", a: "৯৯", b: "১০০", c: "৯৮", d: "১০১", ans: "a" },
            { q: "আল্লাহর সবচেয়ে বড় নাম কোনটি?", a: "আল্লাহ", b: "রহমান", c: "রহিম", d: "মালিক", ans: "a" },
            { q: "কোন সূরায় 'বিসমিল্লাহ' ছাড়া শুরু হয়?", a: "সূরা তওবা", b: "সূরা ফাতিহা", c: "সূরা বাকারা", d: "সূরা ইমরান", ans: "a" },
            { q: "কুরআনের প্রথম আয়াত কোন সূরায়?", a: "সূরা আলাক", b: "সূরা ফাতিহা", c: "সূরা বাকারা", d: "সূরা ইমরান", ans: "a" },
            { q: "আল্লাহর সিংহাসনের নাম কী?", a: "আরশ", b: "কুরসি", c: "উভয়", d: "কোনটিই নয়", ans: "a" },
            { q: "আল্লাহর পায়ার নাম কী?", a: "কুরসি", b: "আরশ", c: "উভয়", d: "কোনটিই নয়", ans: "a" },
            { q: "আল্লাহর সবচেয়ে প্রিয় কাজ কী?", a: "নামাজ", b: "যাকাত", c: "হজ", d: "তওবা", ans: "a" },
            { q: "ইসলামে সবচেয়ে গুনাহ কোনটি?", a: "শিরক", b: "মিথ্যা বলা", c: "চুরি", d: "হত্যা", ans: "a" },
            { q: "কোন কাজে আল্লাহ সবচেয়ে খুশি হন?", a: "তওবা", b: "নামাজ", c: "যাকাত", d: "হজ", ans: "a" },
            { q: "কোন কাজে আল্লাহ সবচেয়ে নাখোশ হন?", a: "শিরক", b: "মিথ্যা", c: "চুরি", d: "হত্যা", ans: "a" },
            { q: "সাবর কী?", a: "ধৈর্য", b: "শুকর", c: "তওবা", d: "ইস্তিগফার", ans: "a" },
            { q: "শুকর কী?", a: "কৃতজ্ঞতা", b: "ধৈর্য", c: "তওবা", d: "ইস্তিগফার", ans: "a" },
            { q: "তওবা কী?", a: "পাপ থেকে ফিরে আসা", b: "পাপ করা", c: "পাপকে ভালো বলা", d: "পাপ গোপন করা", ans: "a" },
            { q: "ইস্তিগফার কী?", a: "ক্ষমা চাওয়া", b: "পাপ করা", c: "পাপ গোপন করা", d: "পাপকে ভালো বলা", ans: "a" },
            { q: "কিয়ামতের আগে কী হবে?", a: "দাজ্জালের আবির্ভাব", b: "ঈসা (আ.)-এর আগমন", c: "ইয়াজুজ-মাজুজ", d: "উভয়", ans: "a" },
            { q: "দাজ্জাল কে?", a: "একজন প্রতারক", b: "ফেরেশতা", c: "নবী", d: "সাহাবী", ans: "a" },
            { q: "ঈসা (আ.) কখন আসবেন?", a: "কিয়ামতের আগে", b: "কিয়ামতের পরে", c: "কিয়ামতের দিন", d: "কখনো আসবেন না", ans: "a" },
            { q: "ইয়াজুজ-মাজুজ কারা?", a: "একটি জাতি", b: "ফেরেশতা", c: "নবীগণ", d: "সাহাবীগণ", ans: "a" },
            { q: "কিয়ামতের আলামত কয়টি?", a: "১০টি ছোট, ১০টি বড়", b: "৫টি ছোট, ৫টি বড়", c: "১৫টি ছোট, ১৫টি বড়", d: "২০টি ছোট, ২০টি বড়", ans: "a" },
            { q: "জান্নাতের উঁচু স্তরকে কী বলে?", a: "ফেরদাউস", b: "আদন", c: "মাওয়া", d: "খুলদ", ans: "a" },
            { q: "জাহান্নামের নিচু স্তরকে কী বলে?", a: "হুতামা", b: "সাকার", c: "লাযা", d: "জাহিম", ans: "a" },
            { q: "পুলসিরাত কিসের ওপর স্থাপিত?", a: "জাহান্নামের ওপর", b: "জান্নাতের ওপর", c: "পৃথিবীর ওপর", d: "আকাশের ওপর", ans: "a" },
            { q: "হাউজে কাউসার কী?", a: "নবীজির পুকুর", b: "জান্নাতের নদী", c: "জাহান্নামের নদী", d: "পৃথিবীর নদী", ans: "a" },
            { q: "মিজান কী?", a: "নেকি-গুনাহের দাঁড়িপাল্লা", b: "জান্নাতের সেতু", c: "জাহান্নামের সেতু", d: "কিয়ামতের সেতু", ans: "a" },
            { q: "কিয়ামতের দিন মানুষের কয়টি অবস্থা হবে?", a: "৩", b: "৪", c: "৫", d: "৬", ans: "a" },
            { q: "আমলনামা কেমন হবে?", a: "ডান হাতে বা বাম হাতে", b: "সবাই ডান হাতে", c: "সবাই বাম হাতে", d: "সবার একই", ans: "a" },
            { q: "কিয়ামতের হিসাব কতক্ষণ চলবে?", a: "৫০ হাজার বছর", b: "১০ হাজার বছর", c: "১০০ হাজার বছর", d: "১ লাখ বছর", ans: "a" },
            { q: "কিয়ামতের সময় কী হবে?", a: "সবকিছু ধ্বংস", b: "সবকিছু নতুন", c: "সবকিছু আলাদা", d: "সবকিছু একই", ans: "a" },
            { q: "কিয়ামতের পর কী হবে?", a: "হাশর-নশর", b: "জান্নাত-জাহান্নাম", c: "উভয়", d: "কোনটিই নয়", ans: "a" },
            { q: "জান্নাতের সুখ কেমন?", a: "অফুরন্ত", b: "সীমিত", c: "শারীরিক", d: "আত্মিক", ans: "a" },
            { q: "জাহান্নামের শাস্তি কেমন?", a: "চিরস্থায়ী", b: "অস্থায়ী", c: "শারীরিক", d: "আত্মিক", ans: "a" },
            { q: "আল্লাহর রহমত কীসের চেয়ে বেশি?", a: "আল্লাহর গজব", b: "শয়তানের প্রভাব", c: "মানুষের পাপ", d: "ফেরেশতার ইবাদত", ans: "a" },
            { q: "আয়াতুল কুরসি কোন সূরায়?", a: "সূরা বাকারা", b: "সূরা ইমরান", c: "সূরা নিসা", d: "সূরা মায়িদা", ans: "a" },
            { q: "কুরআনের সর্বশেষ সূরা কোনটি?", a: "সূরা নাস", b: "সূরা ফালাক", c: "সূরা ইখলাস", d: "সূরা কাউসার", ans: "a" },
            { q: "নবীজির সবচেয়ে প্রিয় স্ত্রী কে ছিলেন?", a: "আয়েশা (রা.)", b: "হাফসা (রা.)", c: "সাওদা (রা.)", d: "জয়নব (রা.)", ans: "a" },
            { q: "নবীজির চাচা যিনি ইসলাম গ্রহণ করেননি তার নাম কী?", a: "আবু লাহাব", b: "হামজা", c: "আব্বাস", d: "আবু তালিব", ans: "a" },
            { q: "কারবালার ঘটনা কোন মাসে ঘটে?", a: "মুহাররম", b: "রমজান", c: "রজব", d: "শাওয়াল", ans: "a" },
            { q: "ইমাম হুসাইন (রা.) কার সন্তান ছিলেন?", a: "আলী (রা.)", b: "উমর (রা.)", c: "উসমান (রা.)", d: "আবু বকর (রা.)", ans: "a" }
        ];

        const hardQuestions = [
            { q: "কুরআনের কোন সূরায় বাধ্যতামূলক সিজদা আছে?", a: "সূরা আলাক", b: "সূরা বাকারা", c: "সূরা ইমরান", d: "সূরা নিসা", ans: "a" },
            { q: "সূরা বাকারার শেষ দুই আয়াতকে কী বলে?", a: "আমানার রাসূল", b: "আয়াতুল কুরসি", c: "খাতামাতুল বাকারা", d: "সূরা ফাতিহা", ans: "a" },
            { q: "কোন সূরায় বাকারার উল্লেখ আছে?", a: "সূরা বাকারা", b: "সূরা ইমরান", c: "সূরা নিসা", d: "সূরা মায়িদা", ans: "a" },
            { q: "সাইয়্যিদুল ইস্তিগফার কী?", a: "আল্লাহুম্মা আন্তা রাব্বি", b: "সুবহানাল্লাহ", c: "আলহামদুলিল্লাহ", d: "লা ইলাহা ইল্লাল্লাহ", ans: "a" },
            { q: "দাজ্জালের আবির্ভাব কোথায় হবে?", a: "পূর্ব দিকে", b: "পশ্চিম দিকে", c: "উত্তর দিকে", d: "দক্ষিণ দিকে", ans: "a" },
            { q: "ঈসা (আ.) কোথায় নাযিল হবেন?", a: "দামেস্ক", b: "মক্কা", c: "মদিনা", d: "কুফা", ans: "a" },
            { q: "ইয়াজুজ-মাজুজ কোথা থেকে বের হবে?", a: "চীনের দেয়ালের পিছনে", b: "আরব", c: "আফ্রিকা", d: "ইউরোপ", ans: "a" },
            { q: "সূর্য কোথা থেকে উদিত হবে?", a: "পশ্চিম থেকে", b: "পূর্ব থেকে", c: "উত্তর থেকে", d: "দক্ষিণ থেকে", ans: "a" },
            { q: "কিয়ামতের দিন মানুষ কোথায় জমায়েত হবে?", a: "ময়দানে মাহশর", b: "জান্নাত", c: "জাহান্নাম", d: "আরাফাত", ans: "a" },
            { q: "জান্নাতের নাম কয়টি?", a: "৮", b: "৭", c: "৬", d: "৫", ans: "a" },
            { q: "জাহান্নামের নাম কয়টি?", a: "৭", b: "৮", c: "৬", d: "৫", ans: "a" },
            { q: "জান্নাতের সর্বোচ্চ স্তর কোনটি?", a: "ফেরদাউস", b: "আদন", c: "মাওয়া", d: "খুলদ", ans: "a" },
            { q: "জাহান্নামের সর্বনিম্ন স্তর কোনটি?", a: "হুতামা", b: "সাকার", c: "লাযা", d: "জাহিম", ans: "a" },
            { q: "পুলসিরাত কত দিনের পথ?", a: "৫০০ বছর", b: "১০০০ বছর", c: "৫০ হাজার বছর", d: "১০ হাজার বছর", ans: "a" },
            { q: "হাউজে কাউসারের পানি কেমন?", a: "দুধের চেয়ে সাদা", b: "মধুর চেয়ে মিষ্টি", c: "উভয়", d: "কোনটিই নয়", ans: "a" },
            { q: "মিজানের পাল্লা কেমন?", a: "২টি", b: "৩টি", c: "৪টি", d: "১টি", ans: "a" },
            { q: "আমলনামা কোথা থেকে পড়া হবে?", a: "ডান হাত থেকে", b: "বাম হাত থেকে", c: "উভয়", d: "কোনটিই নয়", ans: "a" },
            { q: "জান্নাতের নিচে কী প্রবাহিত হয়?", a: "নদী", b: "আগুন", c: "ধোঁয়া", d: "পাথর", ans: "a" },
            { q: "জাহান্নামের আগুন কেমন?", a: "সর্বদা জ্বলন্ত", b: "কখনো জ্বলে, কখনো নিভে", c: "ঠান্ডা", d: "নিরাপদ", ans: "a" },
            { q: "তওরাত কার ওপর নাযিল হয়?", a: "মুসা", b: "ঈসা", c: "দাউদ", d: "মুহাম্মদ", ans: "a" },
            { q: "ইঞ্জিল কার ওপর নাযিল হয়?", a: "ঈসা", b: "মুসা", c: "দাউদ", d: "মুহাম্মদ", ans: "a" },
            { q: "যাবুর কার ওপর নাযিল হয়?", a: "দাউদ", b: "মুসা", c: "ঈসা", d: "মুহাম্মদ", ans: "a" },
            { q: "কুরআন কার ওপর নাযিল হয়?", a: "মুহাম্মদ", b: "মুসা", c: "ঈসা", d: "দাউদ", ans: "a" },
            { q: "সুহুফ কার ওপর নাযিল হয়?", a: "ইব্রাহিম ও মুসা", b: "দাউদ", c: "ঈসা", d: "মুহাম্মদ", ans: "a" },
            { q: "আল্লাহর কোন সিফাত সবচেয়ে বড়?", a: "কুদরত", b: "ইলম", c: "হায়াত", d: "ইরাদা", ans: "a" },
            { q: "আল্লাহর কোন সিফাত 'সবকিছু জানা'?", a: "ইলম", b: "কুদরত", c: "হায়াত", d: "ইরাদা", ans: "a" },
            { q: "আল্লাহর কোন সিফাত 'সবকিছু করার ক্ষমতা'?", a: "কুদরত", b: "ইলম", c: "হায়াত", d: "ইরাদা", ans: "a" },
            { q: "আল্লাহর কোন সিফাত 'চিরঞ্জীব'?", a: "হায়াত", b: "ইলম", c: "কুদরত", d: "ইরাদা", ans: "a" },
            { q: "আল্লাহর কোন সিফাত 'ইচ্ছা'?", a: "ইরাদা", b: "ইলম", c: "কুদরত", d: "হায়াত", ans: "a" },
            { q: "বনী ইসরাঈল কাকে বলে?", a: "হযরত ইয়াকুবের সন্তান", b: "হযরত ইব্রাহিমের সন্তান", c: "হযরত ইসমাইলের সন্তান", d: "হযরত ইসহাকের সন্তান", ans: "a" },
            { q: "হিজরতের সময় নবীজির সঙ্গী কে ছিলেন?", a: "আবু বকর (রা.)", b: "উমর (রা.)", c: "উসমান (রা.)", d: "আলী (রা.)", ans: "a" },
            { q: "ইসলামের দ্বিতীয় খলিফা কে?", a: "উমর", b: "আবু বকর", c: "উসমান", d: "আলী", ans: "a" },
            { q: "ইসলামের তৃতীয় খলিফা কে?", a: "উসমান", b: "উমর", c: "আবু বকর", d: "আলী", ans: "a" },
            { q: "ইসলামের চতুর্থ খলিফা কে?", a: "আলী", b: "উসমান", c: "উমর", d: "আবু বকর", ans: "a" },
            { q: "আল্লাহর কয়টি আসমান?", a: "৭", b: "৫", c: "৩", d: "৯", ans: "a" },
            { q: "আল্লাহর কয়টি জাহান্নাম?", a: "৭", b: "৫", c: "৩", d: "৯", ans: "a" },
            { q: "আল্লাহর কয়টি জান্নাত?", a: "৮", b: "৭", c: "৬", d: "৫", ans: "a" },
            { q: "আল্লাহর আরশ কয়টি ফেরেশতা বহন করে?", a: "৪", b: "৫", c: "৬", d: "৭", ans: "a" },
            { q: "আল্লাহর সিংহাসন কয়টি?", a: "১", b: "২", c: "৩", d: "৪", ans: "a" },
            { q: "আল্লাহর কুরসি কয়টি?", a: "১", b: "২", c: "৩", d: "৪", ans: "a" },
            { q: "আল্লাহর আরশ ও কুরসি কি এক?", a: "না, আলাদা", b: "হ্যাঁ, এক", c: "অংশ", d: "কোনটিই নয়", ans: "a" },
            { q: "আল্লাহর আরশের চারপাশে কারা তাসবিহ পাঠ করেন?", a: "ফেরেশতাগণ", b: "নবীগণ", c: "সাহাবীগণ", d: "জ্বিনগণ", ans: "a" },
            { q: "আল্লাহর কুরসি কোথায়?", a: "আরশের নিচে", b: "আরশের উপরে", c: "আরশের পাশে", d: "আরশের বিপরীতে", ans: "a" },
            { q: "আল্লাহর আরশ কিসের তৈরি?", a: "নূর", b: "আলো", c: "আগুন", d: "পানি", ans: "a" },
            { q: "আল্লাহর কুরসি কিসের তৈরি?", a: "নূর", b: "আলো", c: "আগুন", d: "পানি", ans: "a" },
            { q: "আল্লাহর সিফাত কয়টি?", a: "অসংখ্য", b: "৯৯", c: "১০০", d: "৯৮", ans: "a" },
            { q: "আল্লাহর জাতি সিফাত কয়টি?", a: "৫", b: "৬", c: "৭", d: "৮", ans: "a" },
            { q: "আল্লাহর সালবি সিফাত কয়টি?", a: "৫", b: "৬", c: "৭", d: "৮", ans: "a" },
            { q: "আল্লাহর ফেলী সিফাত কয়টি?", a: "অসংখ্য", b: "৫", c: "৬", d: "৭", ans: "a" },
            { q: "আল্লাহর জাতি সিফাত কোনগুলো?", a: "হায়াত, ইলম, কুদরত, ইরাদা, সামা, বাসার, কালাম", b: "হায়াত, ইলম, কুদরত", c: "ইলম, কুদরত", d: "শুধু হায়াত", ans: "a" },
            { q: "আল্লাহর সালবি সিফাত কোনগুলো?", a: "কাদিম, বাকি, মুখালিফাতুল হাওয়াদিস, কিয়ামু বিনাফসিহি, ওয়াহদানিয়্যাত", b: "হায়াত, ইলম", c: "কুদরত, ইরাদা", d: "সামা, বাসার", ans: "a" },
            { q: "আল্লাহর কালাম কী?", a: "কুরআন", b: "হাদীস", c: "সুন্নাহ", d: "ফিকহ", ans: "a" },
            { q: "আল্লাহর কালাম কিসের তৈরি?", a: "হরফ ও শব্দ", b: "আলো", c: "আগুন", d: "পানি", ans: "a" },
            { q: "আল্লাহর কালাম কি সৃষ্ট?", a: "না, অনাদি", b: "হ্যাঁ, সৃষ্ট", c: "আংশিক", d: "কোনটিই নয়", ans: "a" },
            { q: "আল্লাহর কালাম কয় প্রকার?", a: "২", b: "৩", c: "৪", d: "৫", ans: "a" },
            { q: "আল্লাহর কালামের প্রথম প্রকার?", a: "লাওহে মাহফুজ", b: "কুরআন", c: "হাদীস", d: "সুন্নাহ", ans: "a" },
            { q: "আল্লাহর কালামের দ্বিতীয় প্রকার?", a: "কুরআন", b: "হাদীস", c: "সুন্নাহ", d: "ফিকহ", ans: "a" },
            { q: "আল্লাহর কালাম কোথায় লিপিবদ্ধ?", a: "লাওহে মাহফুজে", b: "আরশে", c: "কুরসিতে", d: "আসমানে", ans: "a" },
            { q: "আল্লাহর কালাম কি পরিবর্তনশীল?", a: "না, চিরন্তন", b: "হ্যাঁ", c: "আংশিক", d: "কোনটিই নয়", ans: "a" },
            { q: "আল্লাহর কালাম কি মাখলুক?", a: "না, গায়রে মাখলুক", b: "হ্যাঁ", c: "আংশিক", d: "কোনটিই নয়", ans: "a" },
            { q: "আল্লাহর আরশ ও কুরসি কি সৃষ্ট?", a: "হ্যাঁ", b: "না", c: "আংশিক", d: "কোনটিই নয়", ans: "a" },
            { q: "আল্লাহর আরশ কখন সৃষ্ট?", a: "অনাদিকাল", b: "আদি সৃষ্টিতে", c: "পরে", d: "কোনটিই নয়", ans: "a" },
            { q: "আল্লাহর কুরসি কখন সৃষ্ট?", a: "অনাদিকাল", b: "আদি সৃষ্টিতে", c: "পরে", d: "কোনটিই নয়", ans: "a" },
            { q: "আল্লাহর আরশ কতদিনে সৃষ্ট?", a: "৬ দিনে", b: "৪ দিনে", c: "২ দিনে", d: "১ দিনে", ans: "a" },
            { q: "আল্লাহর কুরসি কতদিনে সৃষ্ট?", a: "৬ দিনে", b: "৪ দিনে", c: "২ দিনে", d: "১ দিনে", ans: "a" },
            { q: "আল্লাহর আরশ ও কুরসি কি একই?", a: "না, আলাদা", b: "হ্যাঁ", c: "আংশিক", d: "কোনটিই নয়", ans: "a" },
            { q: "আল্লাহর আরশ কিসের উর্ধ্বে?", a: "সবকিছুর", b: "আসমানের", c: "জমিনের", d: "জান্নাতের", ans: "a" },
            { q: "আল্লাহর কুরসি কিসের উর্ধ্বে?", a: "আসমানের", b: "জমিনের", c: "জান্নাতের", d: "জাহান্নামের", ans: "a" },
            { q: "আল্লাহর আরশের নিচে কী আছে?", a: "কুরসি", b: "জান্নাত", c: "জাহান্নাম", d: "পৃথিবী", ans: "a" },
            { q: "আল্লাহর কুরসির নিচে কী আছে?", a: "আসমান", b: "জমিন", c: "জান্নাত", d: "জাহান্নাম", ans: "a" },
            { q: "ইলমে কালামের আলোচ্য বিষয় কী?", a: "আকিদা-বিশ্বাস", b: "ফিকহ", c: "তাজবিদ", d: "হাদীসশাস্ত্র", ans: "a" },
            { q: "উসূলে ফিকহ কী নিয়ে আলোচনা করে?", a: "শরিয়াহ বিধানের উৎস ও পদ্ধতি", b: "শুধু নামাজ", c: "শুধু রোজা", d: "শুধু হজ", ans: "a" },
            { q: "ইজমা শরিয়াহর কততম উৎস হিসেবে গণ্য?", a: "তৃতীয়", b: "প্রথম", c: "দ্বিতীয়", d: "চতুর্থ", ans: "a" },
            { q: "কিয়াস বলতে কী বোঝায়?", a: "সাদৃশ্যের ভিত্তিতে সিদ্ধান্ত", b: "সরাসরি কুরআনের বিধান", c: "হাদীসের বিধান", d: "ইজমার বিধান", ans: "a" },
            { q: "শরিয়াহর মূল উৎস কয়টি বলে অধিকাংশ আলেম মনে করেন?", a: "৪টি (কুরআন, হাদীস, ইজমা, কিয়াস)", b: "২টি", c: "৩টি", d: "৫টি", ans: "a" }
        ];

        // সব প্রশ্ন একত্রে (মোট ২৫০টি) — প্রতিটি প্রশ্নকে কঠিনতা-স্তর ট্যাগ করা হলো (ক্যাটাগরি-ভিত্তিক ফলাফলের জন্য)
        const ALL_QUESTIONS = [
            ...easyQuestions.map(q => ({ ...q, diff: 'easy' })),
            ...mediumQuestions.map(q => ({ ...q, diff: 'medium' })),
            ...hardQuestions.map(q => ({ ...q, diff: 'hard' }))
        ];
        const TOTAL_QUESTIONS_PER_ATTEMPT = 100;

        // ===== অ্যাডমিন কর্তৃক যোগ/মুছে ফেলা প্রশ্ন (কাস্টম প্রশ্ন ম্যানেজমেন্ট) =====
        function getCustomQuestions() {
            return JSON.parse(localStorage.getItem('mp_customQuestions') || '[]');
        }

        function setCustomQuestions(list) {
            localStorage.setItem('mp_customQuestions', JSON.stringify(list));
        }

        function getDeletedQuestionTexts() {
            return JSON.parse(localStorage.getItem('mp_deletedQuestions') || '[]');
        }

        function setDeletedQuestionTexts(list) {
            localStorage.setItem('mp_deletedQuestions', JSON.stringify(list));
        }

        // বিল্ট-ইন প্রশ্নের এডিট (অ্যাডমিন প্যানেল থেকে) — মূল কোড পরিবর্তন না করে override হিসেবে সংরক্ষণ করা হয়
        function getQuestionOverrides() {
            return JSON.parse(localStorage.getItem('mp_questionOverrides') || '{}');
        }

        function setQuestionOverrides(map) {
            localStorage.setItem('mp_questionOverrides', JSON.stringify(map));
        }

        // ===== 📊 প্রশ্ন-ভিত্তিক সঠিক/ভুল পরিসংখ্যান (সব অংশগ্রহণকারী মিলিয়ে, "সবচেয়ে বেশি ভুল হওয়া প্রশ্ন" রিপোর্টের জন্য) =====
        function getQuestionStats() {
            return JSON.parse(localStorage.getItem('mp_questionStats') || '{}');
        }

        function recordQuestionAnswerStat(questionText, isCorrect) {
            const stats = getQuestionStats();
            if (!stats[questionText]) stats[questionText] = { correct: 0, wrong: 0 };
            if (isCorrect) stats[questionText].correct++;
            else stats[questionText].wrong++;
            localStorage.setItem('mp_questionStats', JSON.stringify(stats));
        }

        // সক্রিয় প্রশ্ন-পুল: বিল্ট-ইন (মুছে ফেলা বাদে, এডিট করা থাকলে override সহ) + অ্যাডমিনের যোগ করা কাস্টম প্রশ্ন
        function getActiveQuestionPool() {
            const deleted = new Set(getDeletedQuestionTexts());
            const overrides = getQuestionOverrides();
            const base = ALL_QUESTIONS
                .filter(q => !deleted.has(q.q))
                .map(q => overrides[q.q] ? { ...q, ...overrides[q.q] } : q);
            const custom = getCustomQuestions();
            return [...base, ...custom];
        }

        // ===== 📚 Practice Mode-এর আলাদা প্রশ্ন ব্যাংক (প্রথমবার ৫০টি প্রশ্ন দিয়ে সীড করা হয়, অ্যাডমিন প্যানেল থেকে সম্পূর্ণ পরিচালনাযোগ্য) =====
        function getPracticeQuestions() {
            const stored = localStorage.getItem('mp_practiceQuestions');
            if (stored) return JSON.parse(stored);

            // প্রথমবার সীডিং: যাচাইকৃত সহজ প্রশ্নগুলো থেকে প্রথম ৫০টি নেওয়া হলো (নতুন করে তথ্য তৈরি না করে বিশ্বস্ততা বজায় রাখা হয়েছে)
            const seed = easyQuestions.slice(0, 50).map(q => ({ ...q, diff: 'practice' }));
            localStorage.setItem('mp_practiceQuestions', JSON.stringify(seed));
            return seed;
        }

        function setPracticeQuestions(list) {
            localStorage.setItem('mp_practiceQuestions', JSON.stringify(list));
        }

        function generatePracticeQuizSet() {
            const pool = getPracticeQuestions();
            const shuffled = shuffle([...pool]);
            return shuffled.map(q => shuffleOptions({ ...q, diff: 'practice' }));
        }

        // ===== 📚 Practice Mode প্রশ্ন — অ্যাডমিন CRUD + Import/Export =====
        let editingPracticeQuestionIndex = null;

        function fillPracticeForm(item) {
            document.getElementById('pqText').value = item.q;
            document.getElementById('pqA').value = item.a;
            document.getElementById('pqB').value = item.b;
            document.getElementById('pqC').value = item.c;
            document.getElementById('pqD').value = item.d;
            document.getElementById('pqAns').value = item.ans;
        }

        function clearPracticeForm() {
            ['pqText', 'pqA', 'pqB', 'pqC', 'pqD'].forEach(id => document.getElementById(id).value = '');
            document.getElementById('pqAns').value = 'a';
        }

        function startEditPracticeQuestion(index) {
            const list = getPracticeQuestions();
            const item = list[index];
            if (!item) return;
            editingPracticeQuestionIndex = index;
            fillPracticeForm(item);
            document.getElementById('pqFormTitle').innerText = '✏️ Practice প্রশ্ন এডিট করছেন';
            document.getElementById('pqSaveBtn').innerText = '💾 সেভ করুন';
            document.getElementById('pqCancelBtn').style.display = 'inline-block';
        }

        function cancelEditPracticeQuestion() {
            editingPracticeQuestionIndex = null;
            clearPracticeForm();
            document.getElementById('pqFormTitle').innerText = '📚 Practice Mode প্রশ্ন যোগ করুন';
            document.getElementById('pqSaveBtn').innerText = '➕ যোগ করুন';
            document.getElementById('pqCancelBtn').style.display = 'none';
        }

        function savePracticeQuestionForm() {
            const q = document.getElementById('pqText').value.trim();
            const a = document.getElementById('pqA').value.trim();
            const b = document.getElementById('pqB').value.trim();
            const c = document.getElementById('pqC').value.trim();
            const d = document.getElementById('pqD').value.trim();
            const ans = document.getElementById('pqAns').value;

            if (!q || !a || !b || !c || !d) {
                alert('⚠️ প্রশ্ন ও চারটি অপশনই পূরণ করুন!');
                return;
            }

            const list = getPracticeQuestions();
            const newData = { q, a, b, c, d, ans, diff: 'practice' };

            if (editingPracticeQuestionIndex === null) {
                if (list.some(item => item.q === q)) {
                    alert('⚠️ এই প্রশ্নটি ইতিমধ্যে Practice ব্যাংকে আছে!');
                    return;
                }
                list.push(newData);
                alert('✅ নতুন Practice প্রশ্ন যোগ হয়েছে! মোট: ' + (list.length) + 'টি।');
            } else {
                list[editingPracticeQuestionIndex] = newData;
                alert('✅ Practice প্রশ্নটি আপডেট হয়েছে।');
            }
            setPracticeQuestions(list);
            cancelEditPracticeQuestion();
            renderPracticeQuestionList();
        }

        function deletePracticeQuestion(index) {
            if (!confirm('⚠️ এই Practice প্রশ্নটি মুছে ফেলতে চান?')) return;
            const list = getPracticeQuestions();
            list.splice(index, 1);
            setPracticeQuestions(list);
            renderPracticeQuestionList();
        }

        function renderPracticeQuestionList() {
            const box = document.getElementById('practiceQuestionList');
            if (!box) return;
            const list = getPracticeQuestions();

            box.innerHTML = '';
            const summary = document.createElement('div');
            summary.style.cssText = 'font-size:10px; color:#666; margin-bottom:4px;';
            summary.innerText = `মোট Practice প্রশ্ন: ${list.length}টি`;
            box.appendChild(summary);

            list.forEach((item, i) => {
                const row = document.createElement('div');
                row.className = 'custom-q-item';
                const label = document.createElement('span');
                label.title = item.q;
                label.innerText = item.q.length > 32 ? item.q.slice(0, 32) + '…' : item.q;
                const btnGroup = document.createElement('span');
                btnGroup.style.cssText = 'display:flex; gap:4px;';
                const editBtn = document.createElement('button');
                editBtn.style.background = '#2980b9';
                editBtn.innerText = 'এডিট';
                editBtn.addEventListener('click', () => startEditPracticeQuestion(i));
                const delBtn = document.createElement('button');
                delBtn.innerText = 'মুছুন';
                delBtn.addEventListener('click', () => deletePracticeQuestion(i));
                btnGroup.appendChild(editBtn);
                btnGroup.appendChild(delBtn);
                row.appendChild(label);
                row.appendChild(btnGroup);
                box.appendChild(row);
            });
        }

        function exportPracticeQuestions() {
            const list = getPracticeQuestions();
            const blob = new Blob([JSON.stringify(list, null, 2)], { type: 'application/json' });
            const url = URL.createObjectURL(blob);
            const a = document.createElement('a');
            a.href = url;
            a.download = 'practice-questions-' + new Date().toISOString().slice(0, 10) + '.json';
            document.body.appendChild(a);
            a.click();
            a.remove();
            URL.revokeObjectURL(url);
        }

        function importPracticeQuestions(event) {
            const file = event.target.files[0];
            if (!file) return;
            const reader = new FileReader();
            reader.onload = function(e) {
                try {
                    const imported = JSON.parse(e.target.result);
                    if (!Array.isArray(imported)) throw new Error('not an array');
                    const list = getPracticeQuestions();
                    const existingTexts = new Set(list.map(i => i.q));
                    let added = 0;
                    imported.forEach(item => {
                        if (item.q && item.a && item.b && item.c && item.d && item.ans && !existingTexts.has(item.q)) {
                            list.push({ q: item.q, a: item.a, b: item.b, c: item.c, d: item.d, ans: item.ans, diff: 'practice' });
                            existingTexts.add(item.q);
                            added++;
                        }
                    });
                    setPracticeQuestions(list);
                    renderPracticeQuestionList();
                    alert(`✅ ইম্পোর্ট সম্পন্ন! নতুন যোগ হয়েছে: ${added}টি, মোট: ${list.length}টি।`);
                } catch (err) {
                    alert('❌ ফাইলটি সঠিক JSON ফরম্যাটে নেই। প্রতিটি আইটেমে q, a, b, c, d, ans থাকা আবশ্যক।');
                }
            };
            reader.readAsText(file);
            event.target.value = '';
        }

        // ===== প্রশ্ন শাফল ইউটিলিটি =====
        function shuffle(array) {
            for (let i = array.length - 1; i > 0; i--) {
                const j = Math.floor(Math.random() * (i + 1));
                [array[i], array[j]] = [array[j], array[i]];
            }
            return array;
        }

        function shuffleOptions(question) {
            const options = [
                { key: 'a', text: question.a },
                { key: 'b', text: question.b },
                { key: 'c', text: question.c },
                { key: 'd', text: question.d }
            ];
            shuffle(options);
            const newQuestion = {
                q: question.q,
                ans: question.ans,
                diff: question.diff || 'medium',
                img: question.img || null
            };
            options.forEach((opt, index) => {
                const key = String.fromCharCode(97 + index);
                newQuestion[key] = opt.text;
                if (opt.key === question.ans) newQuestion.ans = key;
            });
            return newQuestion;
        }

        // ===== একবারে ১০০টি ইউনিক প্রশ্ন সিলেক্ট করুন (কোনো প্রশ্ন ২ বার আসবে না) =====
        // সক্রিয় প্রশ্ন-পুল (বিল্ট-ইন + অ্যাডমিনের কাস্টম প্রশ্ন, মুছে ফেলা বাদে) থেকে শাফল করে
        // প্রথম ১০০টি নেওয়া হয়, ফলে একই খেলায় কোনো প্রশ্ন কখনোই পুনরাবৃত্তি হবে না।
        function generateQuizSet() {
            const pool = [...getActiveQuestionPool()];
            shuffle(pool);
            const count = Math.min(TOTAL_QUESTIONS_PER_ATTEMPT, pool.length);
            const selected = pool.slice(0, count);
            // ডুপ্লিকেট সেফটি-চেক (সততার জন্য, সাধারণত দরকার হয় না কারণ pool নিজেই ইউনিক)
            const seen = new Set();
            const finalSet = [];
            for (const q of selected) {
                if (!seen.has(q.q)) {
                    seen.add(q.q);
                    finalSet.push(shuffleOptions(q));
                }
            }
            return finalSet;
        }

        // ===== QUIZ ENGINE (ফ্ল্যাট ১০০ প্রশ্ন, কোনো স্টেপ-জনিত রিপিট বাগ নেই) =====
        let quizQuestions = [];
        let categoryStats = { easy: { c: 0, w: 0 }, medium: { c: 0, w: 0 }, hard: { c: 0, w: 0 } };
        let answerLog = []; // 📖 উত্তর রিভিউ সিস্টেমের জন্য প্রতিটি প্রশ্নের উত্তর রেকর্ড
        let mysteryBoxesOpenedThisSession = 0;

        function startQuizFlow() {
            currentIdx = 0;
            quizQuestions = isPracticeMode ? generatePracticeQuizSet() : generateQuizSet();
            categoryStats = { easy: { c: 0, w: 0 }, medium: { c: 0, w: 0 }, hard: { c: 0, w: 0 } };
            answerLog = [];
            mysteryBoxesOpenedThisSession = 0;

            document.getElementById('startScreen').style.display = 'none';
            document.getElementById('quizContent').style.display = 'block';
            renderQ();
            startTimer();
        }

        function renderQ() {
            const q = quizQuestions[currentIdx];
            const questionNum = currentIdx + 1;
            const totalQ = quizQuestions.length;

            document.getElementById('stepDisplay').innerText = 'প্রশ্ন: ' + toBn(questionNum) + '/' + toBn(totalQ);
            document.getElementById('question').innerHTML = escapeHtml(q.q);

            const imgEl = document.getElementById('questionImage');
            if (q.img) {
                imgEl.src = q.img;
                imgEl.style.display = 'block';
            } else {
                imgEl.style.display = 'none';
                imgEl.removeAttribute('src');
            }

            const totalProgress = (questionNum / totalQ) * 100;
            document.getElementById('progressFill').style.width = totalProgress + '%';

            const optDiv = document.getElementById('options');
            optDiv.innerHTML = '';
            const keys = ['a', 'b', 'c', 'd'];

            keys.forEach(k => {
                const btn = document.createElement('button');
                btn.className = 'option-btn';
                btn.innerText = q[k];
                btn.dataset.key = k;
                btn.onclick = () => check(btn, k);
                optDiv.appendChild(btn);
            });
            document.getElementById('nextBtn').style.display = 'none';
            document.getElementById('signal5050').style.display = 'none';
            toggleLifelineUI();
        }

        // বাংলা সংখ্যায় রূপান্তর (নিরাপদে, XSS-মুক্ত)
        function toBn(num) {
            const bnDigits = ['০', '১', '২', '৩', '৪', '৫', '৬', '৭', '৮', '৯'];
            return String(num).split('').map(ch => (/[0-9]/.test(ch) ? bnDigits[ch] : ch)).join('');
        }

        // XSS প্রতিরোধের জন্য বেসিক এসকেপিং (প্রশ্ন টেক্সট রেন্ডার করার আগে)
        function escapeHtml(str) {
            const div = document.createElement('div');
            div.innerText = str;
            return div.innerHTML;
        }

        // ===== CHECK FUNCTION WITH ALL MYSTERY BOX FEATURES =====
        function check(btn, choiceKey) {
            const q = quizQuestions[currentIdx];
            const all = document.querySelectorAll('.option-btn');

            // যদি স্কিপ অ্যাক্টিভ থাকে, তাহলে সরাসরি স্কিপ করুন
            if (skipQuestionActive) {
                skipQuestionActive = false;
                document.getElementById('signalSkip').style.display = 'none';
                document.getElementById('llSkip').classList.remove('active');
                alert('⏭️ আপনি এই প্রশ্নটি স্কিপ করেছেন! পরবর্তী প্রশ্নে চলে যাচ্ছেন...');
                handleNext();
                return;
            }

            if (choiceKey === q.ans) {
                all.forEach(b => b.classList.add('disabled'));
                btn.classList.add('correct');
                playSound('correct');
                totalTime += 5;
                document.getElementById('time').innerText = toBn(totalTime);

                if (categoryStats[q.diff]) categoryStats[q.diff].c++;
                recordQuestionAnswerStat(q.q, true);
                answerLog.push({ q: q.q, a: q.a, b: q.b, c: q.c, d: q.d, ans: q.ans, selected: choiceKey, correct: true });

                // ডাবল স্কোর চেক
                if (doubleScoreActive) {
                    correctCount += 2;
                    doubleScoreActive = false;
                    document.getElementById('signalDouble').style.display = 'none';
                } else {
                    correctCount++;
                }

                streakCount++;

                if (streakCount === 10) {
                    checkMysteryBox();
                } else {
                    document.getElementById('nextBtn').style.display = 'block';
                }
            } else {
                // ভুল করলে ডাবল স্কোর, স্কিপ, হিন্ট রিসেট
                doubleScoreActive = false;
                document.getElementById('signalDouble').style.display = 'none';
                skipQuestionActive = false;
                document.getElementById('signalSkip').style.display = 'none';
                document.getElementById('llSkip').classList.remove('active');
                hintActive = false;
                hintUsedForCurrentQ = false;
                document.getElementById('signalHint').style.display = 'none';
                document.getElementById('llHint').classList.remove('active');

                wrongCount++;
                streakCount = 0;
                if (categoryStats[q.diff]) categoryStats[q.diff].w++;
                recordQuestionAnswerStat(q.q, false);
                answerLog.push({ q: q.q, a: q.a, b: q.b, c: q.c, d: q.d, ans: q.ans, selected: choiceKey, correct: false });


                if (isGuardActiveNow) {
                    isGuardActiveNow = false;
                    document.getElementById('signalGuard').style.display = 'none';
                    btn.classList.add('wrong');
                    btn.classList.add('disabled');
                    playSound('wrong');
                    totalTime = Math.max(0, totalTime - 5);
                    document.getElementById('time').innerText = toBn(totalTime);
                    alert('🛡️ লাইফ গার্ড বাঁচিয়েছে! কিন্তু -৫ সেকেন্ড ও স্ট্রিক রিসেট!');
                    document.getElementById('nextBtn').style.display = 'block';
                } else {
                    all.forEach(b => b.classList.add('disabled'));
                    btn.classList.add('wrong');
                    playSound('wrong');
                    totalTime = Math.max(0, totalTime - 5);
                    document.getElementById('time').innerText = toBn(totalTime);
                    all.forEach(b => { if (b.dataset.key === q.ans) b.classList.add('correct'); });
                    document.getElementById('nextBtn').style.display = 'block';
                }
            }
        }

        function handleNext() {
            hintUsedForCurrentQ = false;
            currentIdx++;
            if (currentIdx < quizQuestions.length) {
                renderQ();
            } else {
                showFinalResult();
            }
        }

        // ===== SKIP QUESTION FUNCTION =====
        function useSkipQuestion() {
            if (!skipQuestionActive) {
                alert('⚠️ আপনার কাছে স্কিপ প্রশ্নের সুযোগ নেই! মিস্টারি বক্স থেকে সংগ্রহ করুন।');
                return;
            }
            if (!quizActive) return;

            document.getElementById('llSkip').classList.add('active');
            alert('⏭️ "স্কিপ" বাটনটি সক্রিয়! পরবর্তী প্রশ্নে যেতে একটি অপশনে ক্লিক করুন।');
        }

        // ===== HINT FUNCTION =====
        function useHint() {
            if (!hintActive) {
                alert('⚠️ আপনার কাছে হিন্ট নেই! মিস্টারি বক্স থেকে সংগ্রহ করুন।');
                return;
            }
            if (!quizActive) return;
            if (hintUsedForCurrentQ) {
                alert('⚠️ এই প্রশ্নের জন্য হিন্ট আগেই ব্যবহার করেছেন!');
                return;
            }

            const q = quizQuestions[currentIdx];
            const correctAnswer = q[q.ans];
            const firstLetter = correctAnswer.charAt(0);

            hintUsedForCurrentQ = true;
            hintActive = false;
            document.getElementById('signalHint').style.display = 'none';
            document.getElementById('llHint').classList.remove('active');

            alert('💡 হিন্ট: এই প্রশ্নের সঠিক উত্তর "' + firstLetter + '" অক্ষর দিয়ে শুরু হয়!');
            playSound('correct');
        }

        // ===== MYSTERY BOX =====
        function checkMysteryBox() {
            if (streakCount !== 10) return;
            streakCount = 0;

            clearInterval(timer);

            setTimeout(() => {
                const overlay = document.createElement('div');
                overlay.className = 'mystery-overlay';
                overlay.id = 'mysteryOverlay';

                overlay.innerHTML = `
                    <div class="mystery-box-card">
                        <h2 style="margin-bottom:12px; font-size:20px; color:#18661F;">🎁 মিস্টারি বক্স! 🎁</h2>
                        <p style="font-weight:bold; margin-bottom:20px; font-size:13px;">টানা ১০টি সঠিক উত্তর! বক্সে ক্লিক করুন 🎯</p>
                        <div class="mystery-gift-icon" onclick="openMysteryBox(this)">📦</div>
                    </div>
                `;
                document.body.appendChild(overlay);
            }, 400);
        }

        function openMysteryBox(element) {
            element.style.pointerEvents = 'none';
            element.innerText = '🎁';
            mysteryBoxesOpenedThisSession++;

            let reward = mysteryRewards[Math.floor(Math.random() * mysteryRewards.length)];
            let msg = '';

            if (reward === 'bonus') {
                reward = mysteryRewards[Math.floor(Math.random() * mysteryRewards.length)];
                msg = '🎁 বোনাস! আরও ১টি রিওয়ার্ড পেলেন!\n\n';
            }

            if (reward === 'life_restore') {
                const lifelines = ['ll5050', 'llTime', 'llAnswer', 'llPoll', 'llGuard'];
                const used = lifelines.filter(id => {
                    const btn = document.getElementById(id);
                    return btn && btn.disabled;
                });
                if (used.length) {
                    const restore = used[Math.floor(Math.random() * used.length)];
                    const btn = document.getElementById(restore);
                    if (btn) {
                        btn.disabled = false;
                        btn.classList.remove('active');
                        if (restore === 'll5050') state5050 = false;
                        if (restore === 'llTime') stateTime = false;
                        if (restore === 'llAnswer') stateAnswer = false;
                        if (restore === 'llPoll') statePoll = false;
                        if (restore === 'llGuard') stateGuard = false;
                    }
                    msg += '🎁 বোনাস! ১টি লাইফলাইন ফিরে পেলেন!';
                } else {
                    totalTime += 20;
                    document.getElementById('time').innerText = toBn(totalTime);
                    msg += '⏱️ +২০ সেকেন্ড বোনাস! (সব লাইফলাইন আগে থেকেই ব্যবহার করা)';
                }
            } else if (reward === 'guard') {
                isGuardActiveNow = true;
                document.getElementById('signalGuard').style.display = 'inline-block';
                msg += '🛡️ অটো লাইফ গার্ড! (পরবর্তী ১টি ভুল থেকে রক্ষা)';
            } else if (reward === 'time_20') {
                totalTime += 20;
                document.getElementById('time').innerText = toBn(totalTime);
                msg += '⏱️ +২০ সেকেন্ড বোনাস!';
            } else if (reward === 'time_30') {
                totalTime += 30;
                document.getElementById('time').innerText = toBn(totalTime);
                msg += '⏱️ +৩০ সেকেন্ড বোনাস!';
            } else if (reward === 'time_50') {
                totalTime += 50;
                document.getElementById('time').innerText = toBn(totalTime);
                msg += '⏱️ +৫০ সেকেন্ড বোনাস!';
            } else if (reward === 'time_60') {
                totalTime += 60;
                document.getElementById('time').innerText = toBn(totalTime);
                msg += '⏱️ +৬০ সেকেন্ড বোনাস!';
            } else if (reward === 'free_score') {
                correctCount++;
                msg += '🎯 ফ্রি স্কোর! +১ পয়েন্ট!';
            } else if (reward === 'double_score') {
                doubleScoreActive = true;
                document.getElementById('signalDouble').style.display = 'inline-block';
                msg += '🔥 ডাবল স্কোর! পরবর্তী সঠিক উত্তরে +২ পয়েন্ট!';
            } else if (reward === 'skip_question') {
                skipQuestionActive = true;
                document.getElementById('signalSkip').style.display = 'inline-block';
                msg += '⏭️ স্কিপ প্রশ্ন! "স্কিপ" বাটনে ক্লিক করে ব্যবহার করুন!';
            } else if (reward === 'extra_time') {
                totalTime += 30;
                document.getElementById('time').innerText = toBn(totalTime);
                msg += '⏱️ +৩০ সেকেন্ড এক্সট্রা টাইম!';
            } else if (reward === 'hint') {
                hintActive = true;
                hintUsedForCurrentQ = false;
                document.getElementById('signalHint').style.display = 'inline-block';
                msg += '💡 হিন্ট পাওয়া গেল! "হিন্ট" বাটনে ক্লিক করে উত্তর দেখুন!';
            }

            confetti({ particleCount: 150, spread: 80, origin: { y: 0.6 } });

            element.parentElement.innerHTML = `
                <h2 style="color:#18661F; margin-bottom:12px;">🎉 অভিনন্দন!</h2>
                <div style="font-size:50px; margin-bottom:12px;">🎁</div>
                <p style="font-weight:bold; font-size:14px; line-height:1.5; color:#222; white-space:pre-line;">${msg}</p>
                <button class="btn-main" style="margin-top:18px; background:var(--primary); font-size:14px;" onclick="closeMysteryBox()">চালিয়ে যান ➜</button>
            `;
        }

        function closeMysteryBox() {
            const overlay = document.getElementById('mysteryOverlay');
            if (overlay) overlay.remove();
            startTimer();
            handleNext();
        }

        // ===== SCORE CALCULATION =====
        function calculateFinalScore() {
            const deduction = Math.floor(wrongCount / 4);
            const finalScore = Math.max(0, correctCount - deduction);
            return { finalScore, deduction };
        }

        async function showFinalResult() {
            clearInterval(timer);
            quizActive = false;
            document.getElementById('quizContent').style.display = 'none';
            document.getElementById('resultScreen').style.display = 'block';
            document.getElementById('displayPlayerName').innerText = playerName;

            const { finalScore, deduction } = calculateFinalScore();
            const totalQ = quizQuestions.length || TOTAL_QUESTIONS_PER_ATTEMPT;
            document.getElementById('finalScore').innerText = toBn(finalScore);
            document.querySelector('.result-score h1').innerHTML =
                '<span id="finalScore">' + toBn(finalScore) + '</span> / ' + toBn(totalQ);

            document.getElementById('scoreBreakdown').innerHTML =
                `✅ সঠিক: ${toBn(correctCount)} | ❌ ভুল: ${toBn(wrongCount)} | ➖ কাটা: ${toBn(deduction)} (প্রতি ৪ ভুলে ১)`;

            const catBox = document.getElementById('categoryBreakdownBox');
            if (catBox) {
                const labels = { easy: '🟢 সহজ', medium: '🟡 মধ্যম', hard: '🔴 কঠিন' };
                let catHtml = '<div style="text-align:center; font-weight:bold; margin-bottom:6px;">📊 ক্যাটাগরি অনুযায়ী ফলাফল</div>';
                ['easy', 'medium', 'hard'].forEach(k => {
                    const s = categoryStats[k] || { c: 0, w: 0 };
                    const total = s.c + s.w;
                    if (total > 0) {
                        catHtml += `<div style="display:flex; justify-content:space-between; padding:2px 0;">
                            <span>${labels[k]}</span>
                            <span>✅ ${toBn(s.c)} | ❌ ${toBn(s.w)} (মোট ${toBn(total)})</span>
                        </div>`;
                    }
                });
                catBox.innerHTML = catHtml;
            }

            const endTime = new Date();
            const timeTaken = startTime ? Math.round((endTime - startTime) / 1000) : 0;

            // 🏅 XP/লেভেল/ব্যাজ/স্ট্রিক আপডেট (প্র্যাকটিস ও প্রতিযোগিতা উভয় মোডেই)
            const { progress, newBadges, leveledUp } = updateAchievements(playerMobile, finalScore, totalQ, wrongCount);
            renderAchievementBox(progress, newBadges, leveledUp);

            // 📖 উত্তর রিভিউ বাটন (অ্যাডমিন টগল অনুযায়ী; প্র্যাকটিস মোডে সবসময় দেখানো হয়)
            const reviewBtn = document.getElementById('reviewBtn');
            if (reviewBtn) {
                reviewBtn.style.display = (isPracticeMode || getAnswerReviewEnabled()) ? 'block' : 'none';
            }

            if (isPracticeMode) {
                document.getElementById('saveMsg').innerHTML = '🎯 এটি প্র্যাকটিস মোড ছিল — ফলাফল সংরক্ষিত হয়নি ও লিডারবোর্ডে যোগ হয়নি।';
                if (finalScore >= Math.round(totalQ * 0.8)) {
                    confetti({ particleCount: 200, spread: 100, origin: { y: 0.6 } });
                }
                exitQuizSecurityMode();
                return;
            }

            setCompletionTime(playerMobile, timeTaken);

            const scores = getScores();
            scores[playerMobile] = finalScore;
            setScores(scores);

            let savedToServer = false;
            if (isBackendConfigured()) {
                const submitResult = await callBackend({
                    action: 'submitResult',
                    name: playerName,
                    mobile: playerMobile,
                    entryCode: entryCode,
                    correct: correctCount,
                    wrong: wrongCount,
                    score: finalScore,
                    totalQuestions: totalQ,
                    totalTime: timeTaken,
                    tabSwitchWarnings: tabSwitchCount,
                    timestamp: endTime.toISOString()
                });
                savedToServer = !!(submitResult && submitResult.ok);
            }

            updateAdminLeaderboard();
            updateParticipantCount();

            if (finalScore >= Math.round(totalQ * 0.8)) {
                confetti({ particleCount: 200, spread: 100, origin: { y: 0.6 } });
            }

            document.getElementById('saveMsg').innerHTML = savedToServer
                ? '✅ ফলাফল শেয়ার্ড সার্ভারে সংরক্ষিত হয়েছে — সব ডিভাইসে দেখা যাবে!'
                : '✅ ফলাফল এই ডিভাইসে সংরক্ষিত হয়েছে। (⚠️ সার্ভার সংযুক্ত না থাকায় শুধু এই ডিভাইসেই দেখা যাবে)';
            exitQuizSecurityMode();
        }

        // ===== 🏅 রেজাল্ট স্ক্রিনে XP/লেভেল/ব্যাজ দেখানো =====
        function renderAchievementBox(progress, newBadges, leveledUp) {
            const box = document.getElementById('achievementBox');
            if (!box) return;
            let html = `<div style="text-align:center; font-weight:bold; margin-bottom:6px;">🏅 আপনার অগ্রগতি</div>
                <div style="display:flex; justify-content:space-around; text-align:center; margin-bottom:6px;">
                    <div><div style="font-weight:bold; color:var(--primary);">${toBn(progress.xp)}</div><div style="font-size:9px; color:#666;">মোট XP</div></div>
                    <div><div style="font-weight:bold; color:var(--secondary);">${toBn(progress.level)}</div><div style="font-size:9px; color:#666;">লেভেল${leveledUp ? ' 🎉' : ''}</div></div>
                    <div><div style="font-weight:bold; color:#e67e22;">${toBn(progress.streak)}</div><div style="font-size:9px; color:#666;">দিনের ধারা 🔥</div></div>
                </div>`;
            if (newBadges.length > 0) {
                html += '<div style="font-size:10px; text-align:center;">নতুন ব্যাজ অর্জন: ' +
                    newBadges.map(k => BADGE_DEFS[k] ? BADGE_DEFS[k].label : k).join(', ') + '</div>';
            }
            box.innerHTML = html;
        }

        // ===== LIFELINES =====
        function toggleLifelineUI() {
            document.getElementById('ll5050').disabled = state5050;
            document.getElementById('llTime').disabled = stateTime;
            document.getElementById('llAnswer').disabled = stateAnswer;
            document.getElementById('llPoll').disabled = statePoll;
            document.getElementById('llGuard').disabled = stateGuard;
        }

        function use5050() {
            if (state5050 || !quizActive) return;
            const buttons = Array.from(document.querySelectorAll('.option-btn'));
            if (buttons.length === 0 || buttons[0].classList.contains('disabled')) return;

            state5050 = true;
            document.getElementById('ll5050').classList.add('active');
            document.getElementById('signal5050').style.display = 'inline-block';
            toggleLifelineUI();

            const q = quizQuestions[currentIdx];
            let wrongButtons = buttons.filter(b => b.dataset.key !== q.ans);
            shuffle(wrongButtons);
            wrongButtons.slice(0, 2).forEach(b => b.classList.add('hidden-option'));

            playSound('correct');
        }

        function useTimeBonus() {
            if (stateTime || !quizActive) return;
            stateTime = true;
            document.getElementById('llTime').classList.add('active');
            toggleLifelineUI();

            totalTime += 30;
            document.getElementById('time').innerText = toBn(totalTime);
            alert('⏱️ +৩০ সেকেন্ড বোনাস!');
            playSound('correct');
        }

        function useShowAnswer() {
            if (stateAnswer || !quizActive) return;
            const buttons = Array.from(document.querySelectorAll('.option-btn'));
            if (buttons.length === 0 || buttons[0].classList.contains('disabled')) return;

            stateAnswer = true;
            document.getElementById('llAnswer').classList.add('active');
            toggleLifelineUI();

            const q = quizQuestions[currentIdx];
            buttons.forEach(b => {
                b.classList.add('disabled');
                if (b.dataset.key === q.ans) b.classList.add('correct');
            });

            playSound('correct');
            totalTime += 5;
            document.getElementById('time').innerText = toBn(totalTime);
            correctCount++;
            if (categoryStats[q.diff]) categoryStats[q.diff].c++;
            answerLog.push({ q: q.q, a: q.a, b: q.b, c: q.c, d: q.d, ans: q.ans, selected: q.ans, correct: true, viaLifeline: true });
            streakCount++;
            document.getElementById('nextBtn').style.display = 'block';
        }

        function useAudiencePoll() {
            if (statePoll || !quizActive) return;
            const buttons = Array.from(document.querySelectorAll('.option-btn'));
            if (buttons.length === 0 || buttons[0].classList.contains('disabled')) return;

            statePoll = true;
            document.getElementById('llPoll').classList.add('active');
            toggleLifelineUI();

            const q = quizQuestions[currentIdx];
            const keys = ['a', 'b', 'c', 'd'];
            let correctVote = Math.floor(Math.random() * (75 - 55 + 1)) + 55;
            let remaining = 100 - correctVote;

            buttons.forEach((btn, index) => {
                const k = keys[index];
                const pollEl = document.createElement('span');
                pollEl.className = 'poll-percentage';
                pollEl.style.display = 'inline-block';

                if (k === q.ans) {
                    pollEl.innerText = toBn(correctVote) + '%';
                } else {
                    let vote = Math.floor(Math.random() * remaining);
                    remaining -= vote;
                    if (index === keys.length - 1 || remaining < 0) { vote += remaining; remaining = 0; }
                    pollEl.innerText = toBn(vote) + '%';
                }
                btn.appendChild(pollEl);
            });

            playSound('correct');
        }

        function useLifeGuard() {
            if (stateGuard || !quizActive) return;
            stateGuard = true;
            isGuardActiveNow = true;
            document.getElementById('llGuard').classList.add('active');
            document.getElementById('signalGuard').style.display = 'inline-block';
            toggleLifelineUI();

            alert('🛡️ লাইফ গার্ড সক্রিয়! ভুল উত্তরে রক্ষা পাবেন।');
            playSound('correct');
        }

        // ===== TIMER (অ্যাডমিন কন্ট্রোলড ডিউরেশন) =====
        function startTimer() {
            const timerBadge = document.getElementById('timerBadge');
            timer = setInterval(() => {
                totalTime--;
                if (totalTime < 0) totalTime = 0;
                document.getElementById('time').innerText = toBn(totalTime);
                if (totalTime <= 10) {
                    timerBadge.classList.add('pulse');
                    if (totalTime > 0) playSound('tick');
                }
                if (totalTime <= 0) {
                    clearInterval(timer);
                    showFinalResult();
                }
            }, 1000);
        }

        // ===== ENTRY CODE =====
        async function generateEntryCode() {
            if (isBackendConfigured()) {
                const result = await callBackend({ action: 'generateCodes', count: 1, password: SUPER_ADMIN_PASSWORD });
                if (result && result.ok && result.codes && result.codes.length) {
                    const code = result.codes[0];
                    // লোকাল ক্যাশেও রেখে দিন (অফলাইন ফলব্যাক/প্রিন্ট লিস্টের জন্য)
                    const codes = getActiveCodes();
                    codes.push({ code, used: false, generatedAt: new Date().toISOString() });
                    setActiveCodes(codes);

                    alert(`✅ নতুন এন্ট্রি কোড তৈরি হয়েছে (সব ডিভাইসে একই কাজ করবে)!\n\n🎫 কোড: ${code}\n\n📌 এই কোডটি সবাইকে দিন।\n⚠️ কোডটি ১ বার ব্যবহার করা যাবে।`);
                    updateParticipantCount();
                    updateAdminLeaderboard();
                    return code;
                }
                console.warn('⚠️ ব্যাকএন্ডে কোড জেনারেট ব্যর্থ, লোকাল মোডে তৈরি করা হচ্ছে (শুধু এই ডিভাইসে কাজ করবে)।');
            }

            // ===== লোকাল ফলব্যাক =====
            const chars = 'ABCDEFGHJKLMNPQRSTUVWXYZ23456789';
            let code = '';
            for (let i = 0; i < 6; i++) {
                code += chars[Math.floor(Math.random() * chars.length)];
            }

            const codes = getActiveCodes();
            codes.push({ code, used: false, generatedAt: new Date().toISOString() });
            setActiveCodes(codes);

            alert(`✅ নতুন এন্ট্রি কোড তৈরি হয়েছে (লোকাল — শুধু এই ডিভাইসে কাজ করবে)!\n\n🎫 কোড: ${code}\n\n📌 এই কোডটি সবাইকে দিন।\n⚠️ কোডটি ১ বার ব্যবহার করা যাবে।`);

            updateParticipantCount();
            updateAdminLeaderboard();
            return code;
        }

        // ===== 🎫📋 একসাথে অনেকগুলো এন্ট্রি কোড জেনারেট + প্রিন্টযোগ্য তালিকা/QR কোড =====
        async function bulkGenerateEntryCodes() {
            const countInput = document.getElementById('bulkCodeCount');
            const count = Math.max(1, Math.min(500, parseInt(countInput.value, 10) || 50));

            if (isBackendConfigured()) {
                const result = await callBackend({ action: 'generateCodes', count: count, password: SUPER_ADMIN_PASSWORD });
                if (result && result.ok && result.codes && result.codes.length) {
                    const codes = getActiveCodes();
                    const now = new Date().toISOString();
                    result.codes.forEach(code => codes.push({ code, used: false, generatedAt: now }));
                    setActiveCodes(codes);

                    updateParticipantCount();
                    updateAdminLeaderboard();
                    printEntryCodeList(result.codes);
                    alert(`✅ ${result.codes.length}টি নতুন এন্ট্রি কোড তৈরি হয়েছে (সব ডিভাইসে একই কাজ করবে) এবং প্রিন্ট পেজ খোলা হয়েছে!`);
                    return;
                }
                console.warn('⚠️ ব্যাকএন্ডে বাল্ক কোড জেনারেট ব্যর্থ, লোকাল মোডে তৈরি করা হচ্ছে।');
            }

            // ===== লোকাল ফলব্যাক =====
            const chars = 'ABCDEFGHJKLMNPQRSTUVWXYZ23456789';
            const codes = getActiveCodes();
            const existingCodes = new Set(codes.map(c => c.code));
            const newCodes = [];

            while (newCodes.length < count) {
                let code = '';
                for (let i = 0; i < 6; i++) code += chars[Math.floor(Math.random() * chars.length)];
                if (existingCodes.has(code)) continue;
                existingCodes.add(code);
                newCodes.push(code);
                codes.push({ code, used: false, generatedAt: new Date().toISOString() });
            }

            setActiveCodes(codes);
            updateParticipantCount();
            updateAdminLeaderboard();
            printEntryCodeList(newCodes);
            alert(`✅ ${newCodes.length}টি নতুন এন্ট্রি কোড তৈরি হয়েছে (লোকাল — শুধু এই ডিভাইসে কাজ করবে) এবং প্রিন্ট পেজ খোলা হয়েছে!`);
        }

        function printEntryCodeList(codeList) {
            const printWin = window.open('', '_blank');
            if (!printWin) {
                alert('⚠️ পপ-আপ ব্লক করা আছে। ব্রাউজারে এই সাইটের জন্য পপ-আপ অনুমতি দিন এবং আবার চেষ্টা করুন।');
                return;
            }

            const baseUrl = window.location.origin + window.location.pathname;
            let cardsHtml = '';
            codeList.forEach((code, i) => {
                cardsHtml += `<div class="code-card">
                    <div class="qr-holder" id="qr-${i}"></div>
                    <div class="code-text">${code}</div>
                </div>`;
            });

            printWin.document.write(`
                <!DOCTYPE html>
                <html lang="bn">
                <head>
                <meta charset="UTF-8">
                <title>এন্ট্রি কোড তালিকা — গাউসিয়া কমিটি কুইজ</title>
                <script src="https://cdn.jsdelivr.net/npm/qrcode@1.5.3/build/qrcode.min.js"><\\/script>
                <style>
                    body { font-family: 'Segoe UI', 'SolaimanLipi', sans-serif; padding: 20px; color: #222; }
                    h1 { text-align:center; color:#18661F; margin-bottom:4px; }
                    .sub { text-align:center; color:#666; margin-bottom:20px; font-size:13px; }
                    .grid { display:grid; grid-template-columns: repeat(auto-fill, minmax(150px, 1fr)); gap:14px; }
                    .code-card { border:2px dashed #18661F; border-radius:10px; padding:10px; text-align:center; page-break-inside: avoid; }
                    .qr-holder { display:flex; justify-content:center; margin-bottom:6px; }
                    .code-text { font-weight:bold; font-size:16px; letter-spacing:2px; color:#1e3c72; }
                    @media print { body { padding: 10px; } }
                </style>
                </head>
                <body>
                    <h1>🎫 গাউসিয়া কমিটি বাংলাদেশ — এন্ট্রি কোড তালিকা</h1>
                    <div class="sub">মোট ${codeList.length}টি কোড — প্রতিটি একবার ব্যবহারযোগ্য। QR কোড স্ক্যান করলে সরাসরি কোড ভরা অবস্থায় প্রতিযোগিতার পেজ খুলবে।</div>
                    <div class="grid" id="codeGrid">${cardsHtml}</div>
                    <script>
                        const base = ${JSON.stringify(baseUrl)};
                        const codes = ${JSON.stringify(codeList)};
                        codes.forEach((code, i) => {
                            const url = base + '?code=' + code;
                            const holder = document.getElementById('qr-' + i);
                            const canvas = document.createElement('canvas');
                            if (window.QRCode && holder) {
                                QRCode.toCanvas(canvas, url, { width: 110, margin: 1 }, function(err) {
                                    if (!err) holder.appendChild(canvas);
                                });
                            }
                        });
                        window.onload = () => setTimeout(() => window.print(), 700);
                    <\\/script>
                </body>
                </html>
            `);
            printWin.document.close();
            printWin.focus();
        }

        // ===== এন্ট্রি কোড ভেরিফাইড আছে কিনা ও সততার অঙ্গীকার টিক দেওয়া আছে কিনা — দুটো মিলিয়ে বাটন সক্রিয়/নিষ্ক্রিয় করা =====
        function updateStartButtonState() {
            const btn = document.getElementById('startBtn');
            const pledge = document.getElementById('honestyPledge');
            if (!btn || !pledge) return;
            if (localStorage.getItem('mp_deviceParticipated') === 'true') return; // এই অবস্থায় বাটন সবসময় নিষ্ক্রিয় থাকবে
            btn.disabled = !(isEntryVerified && pledge.checked);
        }

        async function verifyEntryCode() {
            const code = document.getElementById('entryCode').value.trim().toUpperCase();
            const statusDiv = document.getElementById('entryStatus');

            if (!code || code.length < 4) {
                statusDiv.className = 'status-message error';
                statusDiv.innerText = '❌ সঠিক কোড দিন!';
                return;
            }

            statusDiv.className = 'status-message pending';
            statusDiv.innerText = '⏳ যাচাই করা হচ্ছে...';

            if (isBackendConfigured()) {
                const result = await callBackend({ action: 'verifyCode', code: code });
                if (result && result.ok) {
                    if (result.valid) {
                        isEntryVerified = true;
                        entryCode = code;
                        statusDiv.className = 'status-message success';
                        statusDiv.innerText = '✅ কোড ভেরিফাইড (সার্ভার থেকে)! এখন নিবন্ধন করুন।';
                        document.getElementById('startBtn').innerText = '📝 কুইজ শুরু করুন';
                        updateStartButtonState();
                    } else {
                        statusDiv.className = 'status-message error';
                        statusDiv.innerText = result.reason === 'already_used'
                            ? '❌ এই কোডটি ইতিমধ্যে ব্যবহার করা হয়েছে!'
                            : '❌ কোডটি সঠিক নয়!';
                        isEntryVerified = false;
                        document.getElementById('startBtn').disabled = true;
                    }
                    return; // সার্ভার সিদ্ধান্তমূলক উত্তর দিয়েছে, লোকাল ফলব্যাক দরকার নেই
                }
                statusDiv.innerText = '⚠️ সার্ভারে সংযোগ করা যায়নি, লোকাল মোডে যাচাই করা হচ্ছে...';
            }

            // ===== লোকাল ফলব্যাক (ব্যাকএন্ড কনফিগার না থাকলে বা সাড়া না দিলে) =====
            const codes = getActiveCodes();
            const idx = codes.findIndex(c => c.code === code && !c.used);

            if (idx === -1) {
                statusDiv.className = 'status-message error';
                statusDiv.innerText = '❌ কোড ভুল বা ইতিমধ্যে ব্যবহার করা হয়েছে!';
                isEntryVerified = false;
                document.getElementById('startBtn').disabled = true;
                return;
            }

            codes[idx].used = true;
            setActiveCodes(codes);

            isEntryVerified = true;
            entryCode = code;
            statusDiv.className = 'status-message success';
            statusDiv.innerText = '✅ কোড ভেরিফাইড! এখন নিবন্ধন করুন।';
            document.getElementById('startBtn').innerText = '📝 কুইজ শুরু করুন';
            updateStartButtonState();
        }

        // ===== REGISTRATION (ডিভাইস-লেভেল ডুপ্লিকেট প্রতিরোধ সহ) =====
        async function registerAndStart() {
            isPracticeMode = false;
            if (!isEntryVerified) {
                alert('❌ এন্ট্রি কোড ভেরিফাই করুন!');
                return;
            }

            const honestyChecked = document.getElementById('honestyPledge').checked;
            if (!honestyChecked) {
                alert('⚠️ কুইজ শুরু করার আগে সততার অঙ্গীকার বক্সে টিক দিন।');
                return;
            }

            playerName = document.getElementById('playerName').value.trim();
            playerMobile = document.getElementById('playerMobile').value.trim();

            if (!playerName) return alert('নাম দিন!');
            if (!/^\d{11}$/.test(playerMobile)) return alert('সঠিক মোবাইল নাম্বার দিন!');

            const startBtn = document.getElementById('startBtn');
            startBtn.disabled = true;
            startBtn.innerText = '⏳ যাচাই করা হচ্ছে...';

            // ===== প্রতিযোগিতা চালু আছে কিনা — ব্যাকএন্ড থাকলে সবার জন্য একই উত্তর, না থাকলে লোকাল =====
            let competitionActive;
            if (isBackendConfigured()) {
                const statusResult = await callBackend({ action: 'getStatus' });
                competitionActive = statusResult && statusResult.ok ? statusResult.active : getCompetitionStatus();
            } else {
                competitionActive = getCompetitionStatus();
            }
            if (!competitionActive) {
                startBtn.disabled = false;
                updateStartButtonState();
                return alert('⏳ কম্পিটিশন এখনো শুরু হয়নি!');
            }

            // ===== মোবাইল ডুপ্লিকেট চেক — ব্যাকএন্ড থাকলে সব ডিভাইস মিলিয়ে, না থাকলে শুধু এই ডিভাইসে =====
            let duplicate = false;
            let registeredViaBackend = false;
            if (isBackendConfigured()) {
                const regResult = await callBackend({ action: 'registerParticipant', name: playerName, mobile: playerMobile, entryCode: entryCode });
                if (regResult && regResult.ok) {
                    duplicate = !!regResult.duplicate;
                    registeredViaBackend = !duplicate;
                } else {
                    // সার্ভারে পৌঁছানো যায়নি — লোকাল ফলব্যাক চেকে যাচ্ছি
                    const participants = getParticipants();
                    duplicate = participants.some(p => p.mobile === playerMobile);
                }
            } else {
                const participants = getParticipants();
                duplicate = participants.some(p => p.mobile === playerMobile);
            }

            if (duplicate) {
                startBtn.disabled = false;
                updateStartButtonState();
                return alert('⚠️ এই মোবাইল নম্বর দিয়ে ইতিমধ্যে নিবন্ধন করা হয়েছে! (অন্য ডিভাইস থেকে হলেও ধরা পড়বে যদি সার্ভার সংযুক্ত থাকে)');
            }

            // ডিভাইস-লেভেল ডুপ্লিকেট রক্ষা (একই ব্রাউজার/ডিভাইস থেকে একবারই অংশগ্রহণ — ব্যাকএন্ড থাকুক বা না থাকুক অতিরিক্ত সুরক্ষা হিসেবে থাকছে)
            if (localStorage.getItem('mp_deviceParticipated') === 'true') {
                startBtn.disabled = false;
                updateStartButtonState();
                return alert('⚠️ এই ডিভাইস থেকে ইতিমধ্যে অংশগ্রহণ করা হয়েছে! একাধিকবার অংশগ্রহণ নিয়মবহির্ভূত।');
            }

            if (!registeredViaBackend) {
                const participants = getParticipants();
                participants.push({
                    name: playerName,
                    mobile: playerMobile,
                    entryCode: entryCode,
                    entryVerified: true,
                    registeredAt: new Date().toISOString()
                });
                setParticipants(participants);
            }
            localStorage.setItem('mp_deviceParticipated', 'true');

            const scores = getScores();
            if (!scores[playerMobile]) {
                scores[playerMobile] = 0;
                setScores(scores);
            }

            updateParticipantCount();
            updateAdminLeaderboard();

            initAudio();
            if (audioCtx && audioCtx.state === 'suspended') audioCtx.resume();

            startTime = new Date();
            quizActive = true;
            totalTime = getQuizDuration();
            enterQuizSecurityMode();
            startQuizFlow();
        }

        // ===== 🎯 প্র্যাকটিস মোড (এন্ট্রি কোড/নিবন্ধন ছাড়া, স্কোর সংরক্ষণ হয় না) =====
        function startPractice() {
            const name = prompt('অনুশীলনের জন্য আপনার নাম লিখুন (ঐচ্ছিক):');
            isPracticeMode = true;
            playerName = (name && name.trim()) ? name.trim() : 'অতিথি (প্র্যাকটিস)';
            playerMobile = '';
            entryCode = '';

            initAudio();
            if (audioCtx && audioCtx.state === 'suspended') audioCtx.resume();

            startTime = new Date();
            quizActive = true;
            totalTime = getQuizDuration();
            startQuizFlow();
        }

        // ===== COMPETITION MANAGEMENT =====
        function toDatetimeLocalValue(isoStr) {
            if (!isoStr) return '';
            const d = new Date(isoStr);
            const pad = n => String(n).padStart(2, '0');
            return `${d.getFullYear()}-${pad(d.getMonth() + 1)}-${pad(d.getDate())}T${pad(d.getHours())}:${pad(d.getMinutes())}`;
        }

        function showAdminPanel() {
            const panel = document.getElementById('adminPanel');
            if (panel.style.display === 'block') {
                panel.style.display = 'none';
                return;
            }

            const pwd = prompt('🔐 অ্যাডমিন পাসওয়ার্ড দিন:');
            if (pwd === SUPER_ADMIN_PASSWORD) {
                currentAdminRole = 'super';
            } else if (pwd === ADMIN_PASSWORD) {
                currentAdminRole = 'moderator';
            } else {
                currentAdminRole = null;
                if (pwd !== null) alert('❌ ভুল পাসওয়ার্ড!');
                return;
            }

            panel.style.display = 'block';
            document.body.classList.toggle('super-admin-mode', currentAdminRole === 'super');
            document.body.classList.toggle('moderator-mode', currentAdminRole === 'moderator');
            const roleBadge = document.getElementById('adminRoleBadge');
            if (roleBadge) {
                roleBadge.innerText = currentAdminRole === 'super' ? '👑 সুপার অ্যাডমিন' : '🛡️ মডারেটর (সীমিত এক্সেস)';
            }

            updateParticipantCount();
            updateAdminLeaderboard();
            renderScoreChart();
            renderQuestionManagementList();
            renderPracticeQuestionList();
            const durInput = document.getElementById('adminDurationInput');
            if (durInput) durInput.value = Math.round(getQuizDuration() / 60);

            const schedule = getCompetitionSchedule();
            if (schedule) {
                document.getElementById('adminScheduleStart').value = toDatetimeLocalValue(schedule.start);
                document.getElementById('adminScheduleEnd').value = toDatetimeLocalValue(schedule.end);
            }

            const reviewToggle = document.getElementById('answerReviewToggle');
            if (reviewToggle) reviewToggle.checked = getAnswerReviewEnabled();
            const hofToggle = document.getElementById('hallOfFameToggle');
            if (hofToggle) hofToggle.checked = getHallOfFameVisible();
            const luckyInput = document.getElementById('luckyDrawMinInput');
            if (luckyInput) luckyInput.value = getLuckyDrawMinScore();

            const certTemplate = getCertificateTemplate();
            const certColorInput = document.getElementById('certColorInput');
            const certLogoInput = document.getElementById('certLogoInput');
            if (certColorInput) certColorInput.value = certTemplate.color || '#18661F';
            if (certLogoInput) certLogoInput.value = certTemplate.logoEmoji || '🕌';
        }

        function saveQuizDuration() {
            const minutes = parseInt(document.getElementById('adminDurationInput').value, 10);
            if (isNaN(minutes) || minutes <= 0) {
                alert('⚠️ সঠিক মিনিট সংখ্যা দিন (১ বা তার বেশি)!');
                return;
            }
            setQuizDuration(minutes * 60);
            updateHomeTimerDisplay();
            alert(`✅ কুইজের সময়সীমা আপডেট হয়েছে: ${minutes} মিনিট (মোট ${TOTAL_QUESTIONS_PER_ATTEMPT}টি প্রশ্নের জন্য)।`);
        }

        function updateHomeTimerDisplay() {
            const el = document.getElementById('homeTimerDisplay');
            if (el) {
                const mins = Math.round(getQuizDuration() / 60);
                el.innerText = '⏱ প্রতিযোগীর জন্য সময়সীমা: ' + toBn(mins) + ' মিনিট (' + toBn(TOTAL_QUESTIONS_PER_ATTEMPT) + 'টি প্রশ্ন)';
            }
        }

        // ===== প্রতিযোগিতা সময়সূচি সেভ/ক্লিয়ার (অ্যাডমিন) =====
        function saveSchedule() {
            const startVal = document.getElementById('adminScheduleStart').value;
            const endVal = document.getElementById('adminScheduleEnd').value;
            if (!startVal || !endVal) {
                alert('⚠️ শুরু ও শেষ — দুটো সময়ই দিন!');
                return;
            }
            const startISO = new Date(startVal).toISOString();
            const endISO = new Date(endVal).toISOString();
            if (new Date(endISO) <= new Date(startISO)) {
                alert('⚠️ শেষের সময় শুরুর সময়ের পরে হতে হবে!');
                return;
            }
            setCompetitionSchedule(startISO, endISO);
            alert('✅ সময়সূচি সেভ হয়েছে। এখন হোমপেজে স্বয়ংক্রিয় কাউন্টডাউন দেখাবে।');
            renderCountdown();
        }

        function clearSchedule() {
            clearCompetitionSchedule();
            document.getElementById('adminScheduleStart').value = '';
            document.getElementById('adminScheduleEnd').value = '';
            document.getElementById('countdownBox').style.display = 'none';
            alert('✅ সময়সূচি মুছে ফেলা হয়েছে। এখন ম্যানুয়াল স্টার্ট/বন্ধ বাটন দিয়ে নিয়ন্ত্রণ করুন।');
        }

        // ===== হোমপেজে লাইভ কাউন্টডাউন রেন্ডার =====
        function renderCountdown() {
            const schedule = getCompetitionSchedule();
            const box = document.getElementById('countdownBox');
            if (!box) return;
            if (!schedule || !schedule.start || !schedule.end) {
                box.style.display = 'none';
                return;
            }

            const now = new Date();
            const start = new Date(schedule.start);
            const end = new Date(schedule.end);
            box.style.display = 'block';

            function fmt(ms) {
                const totalSec = Math.max(0, Math.floor(ms / 1000));
                const d = Math.floor(totalSec / 86400);
                const h = Math.floor((totalSec % 86400) / 3600);
                const m = Math.floor((totalSec % 3600) / 60);
                const s = totalSec % 60;
                return `${toBn(d)}দিন ${toBn(h)}ঘ ${toBn(m)}মি ${toBn(s)}সে`;
            }

            if (now < start) {
                box.innerHTML = '⏳ প্রতিযোগিতা শুরু হতে বাকি: ' + fmt(start - now);
                setCompetitionStatus(false);
                isCompetitionActive = false;
                document.getElementById('startBtn').disabled = true;
                document.getElementById('startBtn').innerText = '🔒 প্রতিযোগিতা এখনো শুরু হয়নি';
            } else if (now >= start && now <= end) {
                box.innerHTML = '🟢 প্রতিযোগিতা চলছে — শেষ হতে বাকি: ' + fmt(end - now);
                setCompetitionStatus(true);
                isCompetitionActive = true;
                if (localStorage.getItem('mp_deviceParticipated') !== 'true') {
                    document.getElementById('startBtn').disabled = !isEntryVerified;
                    document.getElementById('startBtn').innerText = isEntryVerified ? '📝 কুইজ শুরু করুন' : '🔒 এন্ট্রি কোড দিন';
                }
            } else {
                box.innerHTML = '🔴 প্রতিযোগিতা শেষ হয়ে গেছে (Competition Closed)';
                setCompetitionStatus(false);
                isCompetitionActive = false;
                document.getElementById('startBtn').disabled = true;
                document.getElementById('startBtn').innerText = '⛔ প্রতিযোগিতা শেষ হয়ে গেছে';
                document.getElementById('entrySection').style.display = 'none';
                if (!getHallOfFameVisible()) setHallOfFameVisible(true);
            }
        }

        async function startCompetition() {
            if (!confirm('🚀 কম্পিটিশন শুরু করতে চান?')) return;
            setCompetitionStatus(true);
            isCompetitionActive = true;
            setHallOfFameVisible(false);

            if (isBackendConfigured()) {
                const result = await callBackend({ action: 'setStatus', value: 'true', password: SUPER_ADMIN_PASSWORD });
                if (result && result.ok) {
                    alert('✅ কম্পিটিশন চালু হয়েছে (সব ডিভাইসে)! এখন সবাই অংশ নিতে পারবে।');
                    return;
                }
                console.warn('⚠️ ব্যাকএন্ডে স্ট্যাটাস আপডেট ব্যর্থ, শুধু এই ডিভাইসে চালু হয়েছে।');
            }
            alert('✅ কম্পিটিশন চালু হয়েছে (শুধু এই ডিভাইসে — ব্যাকএন্ড কনফিগার নেই)! এখন সবাই অংশ নিতে পারবে।');
        }

        async function endCompetition() {
            if (!confirm('⏹️ কম্পিটিশন বন্ধ করতে চান?')) return;
            setCompetitionStatus(false);
            isCompetitionActive = false;
            setHallOfFameVisible(true);

            if (isBackendConfigured()) {
                const result = await callBackend({ action: 'setStatus', value: 'false', password: SUPER_ADMIN_PASSWORD });
                if (result && result.ok) {
                    alert('✅ কম্পিটিশন বন্ধ করা হয়েছে (সব ডিভাইসে)! হোমপেজে এখন Hall of Fame দেখানো হবে।');
                    return;
                }
                console.warn('⚠️ ব্যাকএন্ডে স্ট্যাটাস আপডেট ব্যর্থ, শুধু এই ডিভাইসে বন্ধ হয়েছে।');
            }
            alert('✅ কম্পিটিশন বন্ধ করা হয়েছে (শুধু এই ডিভাইসে)! হোমপেজে এখন Hall of Fame দেখানো হবে।');
        }

        // ===== 🌐 সব ডিভাইসে প্রতিযোগিতার স্ট্যাটাস সিঙ্ক করুন (ব্যাকএন্ড থেকে পর্যায়ক্রমে চেক করা হয়) =====
        async function syncCompetitionStatusFromBackend() {
            if (!isBackendConfigured()) return;
            const result = await callBackend({ action: 'getStatus' });
            if (result && result.ok) {
                setCompetitionStatus(result.active);
                isCompetitionActive = result.active;
                if (localStorage.getItem('mp_deviceParticipated') !== 'true') {
                    const btn = document.getElementById('startBtn');
                    if (btn && !result.active) {
                        btn.disabled = true;
                        btn.innerText = '🔒 প্রতিযোগিতা এখনো শুরু হয়নি';
                    } else if (btn && result.active) {
                        updateStartButtonState();
                        if (btn.disabled && isEntryVerified) btn.innerText = '📝 কুইজ শুরু করুন';
                        else if (!isEntryVerified) btn.innerText = '🔒 এন্ট্রি কোড দিন';
                    }
                }
            }
        }

        // ===== 🏆 স্কোর অনুযায়ী র‍্যাংকড লিডারবোর্ড (সমান স্কোরে দ্রুততম সময় অগ্রাধিকার পাবে) =====
        async function getRankedLeaderboard() {
            if (isBackendConfigured()) {
                const result = await callBackend({ action: 'getLeaderboard', limit: 1000 });
                if (result && result.ok && Array.isArray(result.leaderboard)) {
                    return result.leaderboard; // ইতিমধ্যে সার্ভারে সাজানো (স্কোর, তারপর সময়)
                }
                console.warn('⚠️ শেয়ার্ড লিডারবোর্ড আনা যায়নি, শুধু এই ডিভাইসের লোকাল ডেটা দেখানো হচ্ছে।');
            }

            // ===== লোকাল ফলব্যাক (শুধু এই ডিভাইসে জমা হওয়া ফলাফল) =====
            const scores = getScores();
            const participants = getParticipants();
            const times = getCompletionTimes();

            const entries = Object.entries(scores)
                .filter(([, sc]) => sc > 0)
                .map(([mobile, sc]) => {
                    const p = participants.find(part => part.mobile === mobile);
                    return {
                        mobile,
                        name: p ? p.name : 'অজানা',
                        score: sc,
                        timeTaken: times[mobile] !== undefined ? times[mobile] : Infinity
                    };
                });

            entries.sort((a, b) => b.score - a.score || a.timeTaken - b.timeTaken);
            return entries;
        }

        async function declareWinners() {
            if (!confirm('🏅 বিজয়ী ঘোষণা করতে চান?')) return;

            const entries = await getRankedLeaderboard();
            const winners = entries.slice(0, 3);

            let msg = '🏆 **বিজয়ী ঘোষণা (সমান স্কোরে দ্রুততম সময় অগ্রাধিকার পেয়েছে)** 🏆\n\n';
            const medals = ['🥇 স্বর্ণ', '🥈 রৌপ্য', '🥉 ব্রোঞ্জ'];
            const amounts = ['৫,০০০', '৩,০০০', '২,০০০'];

            winners.forEach((w, i) => {
                if (w) {
                    const timeStr = w.timeTaken !== Infinity ? ` | সময়: ${Math.floor(w.timeTaken / 60)} মিনিট ${w.timeTaken % 60} সেকেন্ড` : '';
                    msg += `${medals[i]}: ${w.name} - ${toBn(w.score)}/${toBn(TOTAL_QUESTIONS_PER_ATTEMPT)} (পুরস্কার: ৳${amounts[i]})${timeStr}\n`;
                }
            });

            if (winners.length === 0) {
                msg = '😞 এখনো কেউ অংশগ্রহণ করেনি!';
                alert(msg);
                return;
            }

            alert(msg);
            confetti({ particleCount: 200, spread: 100, origin: { y: 0.6 } });

            if (confirm('🎓 বিজয়ীদের জন্য একে একে সার্টিফিকেট ডাউনলোড করতে চান?')) {
                winners.forEach((w, i) => {
                    if (w) adminGenerateCertificateFor(w.name, w.score, TOTAL_QUESTIONS_PER_ATTEMPT);
                });
            }
        }

        // ===== 🏅 Hall of Fame (পাবলিক, Top 10) =====
        async function showHallOfFame() {
            const entries = (await getRankedLeaderboard()).slice(0, 10);
            const box = document.createElement('div');
            box.className = 'mystery-overlay';
            box.id = 'hallOfFameOverlay';

            const medalFor = (i) => i === 0 ? '🥇' : i === 1 ? '🥈' : i === 2 ? '🥉' : `#${toBn(i + 1)}`;

            let rowsHtml = '';
            if (entries.length === 0) {
                rowsHtml = '<div style="text-align:center; color:#999; padding:20px;">এখনো কেউ কুইজ সম্পন্ন করেনি।</div>';
            } else {
                entries.forEach((e, i) => {
                    rowsHtml += `<div style="display:flex; justify-content:space-between; align-items:center; padding:8px 10px; margin-bottom:4px; border-radius:8px; background:${i < 3 ? 'linear-gradient(135deg,#ffe259,#ffa751)' : '#f8f9fa'};">
                        <span style="font-weight:bold; width:36px;">${medalFor(i)}</span>
                        <span style="flex:1; font-weight:600;">${escapeHtml(e.name)}</span>
                        <span style="font-weight:bold; color:var(--primary); background:white; padding:2px 10px; border-radius:10px;">${toBn(e.score)}/${toBn(TOTAL_QUESTIONS_PER_ATTEMPT)}</span>
                    </div>`;
                });
            }

            box.innerHTML = `
                <div class="mystery-box-card" style="max-width:420px; text-align:left;">
                    <h2 style="text-align:center; color:#18661F; margin-bottom:14px;">🏅 Hall of Fame — Top 10</h2>
                    <div style="max-height:340px; overflow-y:auto;">${rowsHtml}</div>
                    <button class="btn-main" style="margin-top:16px; background:var(--primary);" onclick="document.getElementById('hallOfFameOverlay').remove()">বন্ধ করুন</button>
                </div>
            `;
            document.body.appendChild(box);
        }

        // ===== 🎲 Lucky Draw Winner (অ্যাডমিন-নিয়ন্ত্রিত এলিজিবিলিটি থ্রেশহোল্ড) =====
        async function runLuckyDraw() {
            const minScore = getLuckyDrawMinScore();
            const eligible = (await getRankedLeaderboard()).filter(e => e.score >= minScore);

            if (eligible.length === 0) {
                alert(`😞 ন্যূনতম স্কোর ${toBn(minScore)} বা তার বেশি পেয়েছেন এমন কোনো অংশগ্রহণকারী নেই।`);
                return;
            }

            if (!confirm(`🎲 ${toBn(eligible.length)} জন যোগ্য অংশগ্রহণকারী থেকে লাকি ড্র করতে চান? (ন্যূনতম স্কোর: ${toBn(minScore)})`)) return;

            const winner = eligible[Math.floor(Math.random() * eligible.length)];
            confetti({ particleCount: 250, spread: 120, origin: { y: 0.6 } });
            alert(`🎉 লাকি ড্র বিজয়ী: ${winner.name}\nমোবাইল: ${winner.mobile}\nস্কোর: ${toBn(winner.score)}/${toBn(TOTAL_QUESTIONS_PER_ATTEMPT)}`);
        }

        // ===== 📄 মেধা তালিকা (Merit List) প্রিন্ট/PDF =====
        async function printMeritList() {
            const entries = await getRankedLeaderboard();
            if (entries.length === 0) {
                alert('⚠️ এখনো কোনো ফলাফল নেই।');
                return;
            }

            let rowsHtml = '';
            entries.forEach((e, i) => {
                const timeStr = e.timeTaken !== Infinity ? `${Math.floor(e.timeTaken / 60)} মিনিট ${e.timeTaken % 60} সেকেন্ড` : '-';
                rowsHtml += `<tr>
                    <td>${i + 1}</td>
                    <td>${escapeHtml(e.name)}</td>
                    <td>${e.mobile}</td>
                    <td>${e.score}/${TOTAL_QUESTIONS_PER_ATTEMPT}</td>
                    <td>${timeStr}</td>
                </tr>`;
            });

            const printWin = window.open('', '_blank');
            if (!printWin) {
                alert('⚠️ পপ-আপ ব্লক করা আছে। ব্রাউজারে এই সাইটের জন্য পপ-আপ অনুমতি দিন এবং আবার চেষ্টা করুন।');
                return;
            }

            printWin.document.write(`
                <!DOCTYPE html>
                <html lang="bn">
                <head>
                <meta charset="UTF-8">
                <title>মেধা তালিকা - গাউসিয়া কমিটি কুইজ কম্পিটিশন</title>
                <style>
                    body { font-family: 'Segoe UI', 'SolaimanLipi', sans-serif; padding: 30px; color: #222; }
                    h1 { text-align:center; color:#18661F; margin-bottom:2px; }
                    .sub { text-align:center; color:#666; margin-bottom:20px; font-size:13px; }
                    table { width:100%; border-collapse: collapse; }
                    th, td { border:1px solid #ccc; padding:8px; text-align:left; font-size:13px; }
                    th { background:#18661F; color:white; }
                    tr:nth-child(even) { background:#f8f9fa; }
                    @media print { body { padding: 10px; } }
                </style>
                </head>
                <body>
                    <h1>গাউসিয়া কমিটি বাংলাদেশ — কুইজ কম্পিটিশন ২০২৬</h1>
                    <div class="sub">মেধা তালিকা (Merit List) — মোট অংশগ্রহণকারী: ${entries.length} জন</div>
                    <table>
                        <tr><th>র‍্যাঙ্ক</th><th>নাম</th><th>মোবাইল</th><th>স্কোর</th><th>সময়</th></tr>
                        ${rowsHtml}
                    </table>
                </body>
                </html>
            `);
            printWin.document.close();
            printWin.focus();
            setTimeout(() => printWin.print(), 400);
        }

        function resetAllData() {
            if (!confirm('⚠️ সব ডেটা রিসেট করতে চান? এটি অপরিবর্তনীয়!')) return;
            if (!confirm('আবারও নিশ্চিত করুন: সব অংশগ্রহণকারী ও স্কোর মুছে যাবে!')) return;

            localStorage.removeItem('mp_participants');
            localStorage.removeItem('mp_scores');
            localStorage.removeItem('mp_activeCodes');
            localStorage.removeItem('mp_competitionActive');
            localStorage.removeItem('mp_quizDuration');
            localStorage.removeItem('mp_deviceParticipated');
            localStorage.removeItem('mp_schedule');
            localStorage.removeItem('mp_cheatLogs');
            localStorage.removeItem('mp_activeSession');
            localStorage.removeItem('mp_customQuestions');
            localStorage.removeItem('mp_deletedQuestions');
            localStorage.removeItem('mp_questionOverrides');
            localStorage.removeItem('mp_questionStats');
            localStorage.removeItem('mp_hallOfFameVisible');

            alert('✅ সব ডেটা রিসেট করা হয়েছে!');
            location.reload();
        }

        // ===== UPDATE UI =====
        function updateParticipantCount() {
            const participants = getParticipants();
            document.getElementById('participantCount').innerText = toBn(participants.length);
            document.getElementById('adminTotal').innerText = toBn(participants.length);

            const scores = getScores();
            const active = participants.filter(p => scores[p.mobile] !== undefined && scores[p.mobile] > 0);
            document.getElementById('adminActive').innerText = toBn(active.length);

            const values = Object.values(scores).filter(v => v > 0);
            if (values.length > 0) {
                const avg = values.reduce((a, b) => a + b, 0) / values.length;
                document.getElementById('adminAvg').innerText = toBn(avg.toFixed(1));
                const highEl = document.getElementById('adminHigh');
                const lowEl = document.getElementById('adminLow');
                if (highEl) highEl.innerText = toBn(Math.max(...values));
                if (lowEl) lowEl.innerText = toBn(Math.min(...values));
            }

            const cheatEl = document.getElementById('adminCheatCount');
            if (cheatEl) cheatEl.innerText = toBn(getCheatLogs().length);

            if (document.getElementById('adminPanel').style.display === 'block') {
                renderScoreChart();
            }
        }

        function updateAdminLeaderboard() {
            const scores = getScores();
            const participants = getParticipants();
            const list = document.getElementById('adminLbList');
            const searchInput = document.getElementById('adminSearchInput');
            const searchTerm = searchInput ? searchInput.value.trim().toLowerCase() : '';

            let entries = Object.entries(scores).map(([mobile, sc]) => {
                const p = participants.find(part => part.mobile === mobile);
                return {
                    mobile,
                    name: p ? p.name : 'অজানা',
                    score: sc
                };
            });

            entries.sort((a, b) => b.score - a.score);

            if (searchTerm) {
                entries = entries.filter(e =>
                    e.name.toLowerCase().includes(searchTerm) || e.mobile.includes(searchTerm)
                );
            }

            if (entries.length === 0) {
                list.innerHTML = '<div class="admin-lb-empty">⏳ এখনো কেউ অংশ নেয়নি অথবা কোনো ফলাফল মেলেনি...</div>';
                return;
            }

            let html = '';
            const medals = ['🥇', '🥈', '🥉'];
            entries.forEach((e, i) => {
                const cls = i === 0 ? 'top1' : i === 1 ? 'top2' : i === 2 ? 'top3' : '';
                const medal = i < 3 ? medals[i] : `<span style="color:#888;font-size:10px;">#${i+1}</span>`;
                html += `
                            <div class="admin-lb-item ${cls}">
                                <span class="rank">${medal}</span>
                                <span class="name">${escapeHtml(e.name)}</span>
                                <span class="score">${toBn(e.score)}/${toBn(TOTAL_QUESTIONS_PER_ATTEMPT)}</span>
                            </div>
                        `;
            });

            list.innerHTML = html;
        }

        // ===== CSV/Excel এক্সপোর্ট =====
        function exportCSV() {
            const scores = getScores();
            const participants = getParticipants();
            let csv = 'নাম,মোবাইল,এন্ট্রি কোড,স্কোর\n';
            participants.forEach(p => {
                const sc = scores[p.mobile] !== undefined ? scores[p.mobile] : 0;
                csv += `"${(p.name || '').replace(/"/g, '""')}","${p.mobile}","${p.entryCode || ''}",${sc}\n`;
            });
            const blob = new Blob(['\uFEFF' + csv], { type: 'text/csv;charset=utf-8;' });
            const url = URL.createObjectURL(blob);
            const a = document.createElement('a');
            a.href = url;
            a.download = 'quiz-results-' + new Date().toISOString().slice(0, 10) + '.csv';
            document.body.appendChild(a);
            a.click();
            a.remove();
            URL.revokeObjectURL(url);
        }

        // ===== ব্যাকআপ / রিস্টোর =====
        function backupData() {
            const keys = ['mp_participants', 'mp_scores', 'mp_activeCodes', 'mp_competitionActive', 'mp_quizDuration', 'mp_schedule', 'mp_cheatLogs', 'mp_customQuestions', 'mp_deletedQuestions', 'mp_questionOverrides', 'mp_questionStats', 'mp_practiceQuestions', 'mp_completionTimes', 'mp_certificates', 'mp_certTemplate', 'mp_playerProgress', 'mp_answerReviewEnabled', 'mp_luckyDrawMinScore'];
            const data = {};
            keys.forEach(k => { data[k] = localStorage.getItem(k); });
            const blob = new Blob([JSON.stringify(data, null, 2)], { type: 'application/json' });
            const url = URL.createObjectURL(blob);
            const a = document.createElement('a');
            a.href = url;
            a.download = 'quiz-backup-' + new Date().toISOString().slice(0, 10) + '.json';
            document.body.appendChild(a);
            a.click();
            a.remove();
            URL.revokeObjectURL(url);
        }

        function restoreData(event) {
            const file = event.target.files[0];
            if (!file) return;
            const reader = new FileReader();
            reader.onload = function(e) {
                try {
                    const data = JSON.parse(e.target.result);
                    if (!confirm('⚠️ বর্তমান সব ডেটা প্রতিস্থাপিত হবে। রিস্টোর করতে চান?')) return;
                    Object.keys(data).forEach(k => {
                        if (data[k] !== null && data[k] !== undefined) localStorage.setItem(k, data[k]);
                    });
                    alert('✅ ডেটা রিস্টোর সম্পন্ন হয়েছে।');
                    location.reload();
                } catch (err) {
                    alert('❌ ফাইলটি সঠিক ফরম্যাটে নেই।');
                }
            };
            reader.readAsText(file);
            event.target.value = '';
        }

        // ===== 📊 স্কোর ডিস্ট্রিবিউশন চার্ট (ক্যানভাস, কোনো লাইব্রেরি ছাড়াই) =====
        function renderScoreChart() {
            const canvas = document.getElementById('scoreChartCanvas');
            if (!canvas) return;
            const ctx = canvas.getContext('2d');
            const w = canvas.width, h = canvas.height;
            ctx.clearRect(0, 0, w, h);

            const scores = Object.values(getScores()).filter(v => v > 0);
            const bins = [0, 0, 0, 0, 0]; // 0-20,21-40,41-60,61-80,81-100
            scores.forEach(s => {
                const idx = Math.min(4, Math.floor(s / 20));
                bins[idx]++;
            });
            const maxBin = Math.max(1, ...bins);
            const labels = ['০-২০', '২১-৪০', '৪১-৬০', '৬১-৮০', '৮১-১০০'];
            const barW = w / bins.length;
            const chartH = h - 24;

            ctx.font = '10px sans-serif';
            ctx.textAlign = 'center';
            bins.forEach((count, i) => {
                const barH = (count / maxBin) * (chartH - 10);
                const x = i * barW + barW * 0.2;
                const barWidth = barW * 0.6;
                const y = chartH - barH;
                ctx.fillStyle = '#18661F';
                ctx.fillRect(x, y, barWidth, barH);
                ctx.fillStyle = '#333';
                ctx.fillText(toBn(count), x + barWidth / 2, y - 3 < 10 ? 10 : y - 3);
                ctx.fillStyle = '#666';
                ctx.fillText(labels[i], x + barWidth / 2, chartH + 14);
            });

            if (scores.length === 0) {
                ctx.fillStyle = '#999';
                ctx.fillText('এখনো কোনো স্কোর নেই', w / 2, h / 2);
            }
        }

        // ===== 📝 প্রশ্ন ম্যানেজমেন্ট (যোগ/এডিট/মুছুন) — বিল্ট-ইন প্রশ্ন override হিসেবে এডিট হয়, কোড অপরিবর্তিত থাকে =====
        let editingQuestionRef = null; // null | { type: 'custom', index } | { type: 'builtin', originalText }

        function fillQuestionForm(item) {
            document.getElementById('cqText').value = item.q;
            document.getElementById('cqA').value = item.a;
            document.getElementById('cqB').value = item.b;
            document.getElementById('cqC').value = item.c;
            document.getElementById('cqD').value = item.d;
            document.getElementById('cqAns').value = item.ans;
            document.getElementById('cqDiff').value = item.diff || 'medium';
            document.getElementById('cqImg').value = item.img || '';
        }

        function clearQuestionForm() {
            document.getElementById('cqText').value = '';
            document.getElementById('cqA').value = '';
            document.getElementById('cqB').value = '';
            document.getElementById('cqC').value = '';
            document.getElementById('cqD').value = '';
            document.getElementById('cqAns').value = 'a';
            document.getElementById('cqDiff').value = 'medium';
            document.getElementById('cqImg').value = '';
        }

        function startEditQuestion(type, ref) {
            let item = null;
            if (type === 'custom') {
                item = getCustomQuestions()[ref];
                editingQuestionRef = { type: 'custom', index: ref };
            } else {
                item = getActiveQuestionPool().find(q => q.q === ref) ||
                       ALL_QUESTIONS.find(q => q.q === ref);
                editingQuestionRef = { type: 'builtin', originalText: ref };
            }
            if (!item) return;
            fillQuestionForm(item);

            document.getElementById('cqFormTitle').innerText = type === 'custom'
                ? '✏️ কাস্টম প্রশ্ন এডিট করছেন'
                : '✏️ বিল্ট-ইন প্রশ্ন এডিট করছেন (override হিসেবে সংরক্ষিত হবে)';
            document.getElementById('cqSaveBtn').innerText = '💾 পরিবর্তন সেভ করুন';
            document.getElementById('cqCancelBtn').style.display = 'inline-block';
            document.getElementById('cqText').scrollIntoView({ behavior: 'smooth', block: 'center' });
        }

        function cancelEditQuestion() {
            editingQuestionRef = null;
            clearQuestionForm();
            document.getElementById('cqFormTitle').innerText = '➕ নতুন প্রশ্ন যোগ করুন';
            document.getElementById('cqSaveBtn').innerText = '➕ প্রশ্ন যোগ করুন';
            document.getElementById('cqCancelBtn').style.display = 'none';
        }

        function saveQuestionForm() {
            const q = document.getElementById('cqText').value.trim();
            const a = document.getElementById('cqA').value.trim();
            const b = document.getElementById('cqB').value.trim();
            const c = document.getElementById('cqC').value.trim();
            const d = document.getElementById('cqD').value.trim();
            const ans = document.getElementById('cqAns').value;
            const diff = document.getElementById('cqDiff').value;
            const img = document.getElementById('cqImg').value.trim();

            if (!q || !a || !b || !c || !d) {
                alert('⚠️ প্রশ্ন ও চারটি অপশনই পূরণ করুন!');
                return;
            }

            const newData = { q, a, b, c, d, ans, diff, img: img || null };

            if (!editingQuestionRef) {
                // নতুন কাস্টম প্রশ্ন যোগ
                const list = getCustomQuestions();
                if (list.some(item => item.q === q) || ALL_QUESTIONS.some(item => item.q === q)) {
                    alert('⚠️ এই প্রশ্নটি ইতিমধ্যে প্রশ্নব্যাংকে আছে!');
                    return;
                }
                list.push(newData);
                setCustomQuestions(list);
                alert('✅ নতুন প্রশ্ন যোগ হয়েছে! মোট প্রশ্নব্যাংক: ' + getActiveQuestionPool().length + 'টি।');
            } else if (editingQuestionRef.type === 'custom') {
                const list = getCustomQuestions();
                list[editingQuestionRef.index] = newData;
                setCustomQuestions(list);
                alert('✅ কাস্টম প্রশ্নটি আপডেট হয়েছে।');
            } else {
                const overrides = getQuestionOverrides();
                overrides[editingQuestionRef.originalText] = newData;
                setQuestionOverrides(overrides);
                alert('✅ বিল্ট-ইন প্রশ্নটি আপডেট হয়েছে (override হিসেবে সংরক্ষিত)।');
            }

            cancelEditQuestion();
            renderQuestionManagementList();
        }

        function deleteCustomQuestion(index) {
            if (!confirm('⚠️ এই কাস্টম প্রশ্নটি মুছে ফেলতে চান?')) return;
            const list = getCustomQuestions();
            list.splice(index, 1);
            setCustomQuestions(list);
            renderQuestionManagementList();
        }

        function deleteBuiltinQuestion(questionText) {
            if (!confirm('⚠️ এই বিল্ট-ইন প্রশ্নটি প্রশ্নব্যাংক থেকে বাদ দিতে চান?')) return;
            const deleted = getDeletedQuestionTexts();
            if (!deleted.includes(questionText)) {
                deleted.push(questionText);
                setDeletedQuestionTexts(deleted);
            }
            // এই প্রশ্নের জন্য থাকা override (যদি থাকে) ও মুছে দিন
            const overrides = getQuestionOverrides();
            if (overrides[questionText]) {
                delete overrides[questionText];
                setQuestionOverrides(overrides);
            }
            renderQuestionManagementList();
            alert('✅ প্রশ্নটি বাদ দেওয়া হয়েছে। মোট সক্রিয় প্রশ্নব্যাংক: ' + getActiveQuestionPool().length + 'টি।');
        }

        function renderQuestionManagementList() {
            const box = document.getElementById('questionMgmtList');
            if (!box) return;

            const custom = getCustomQuestions();
            const deletedCount = getDeletedQuestionTexts().length;
            const overrideCount = Object.keys(getQuestionOverrides()).length;
            const searchInput = document.getElementById('qMgmtSearch');
            const searchTerm = searchInput ? searchInput.value.trim().toLowerCase() : '';

            const summaryDiv = document.createElement('div');
            summaryDiv.style.cssText = 'font-size:10px; color:#666; margin-bottom:4px;';
            summaryDiv.innerText = `মোট সক্রিয় প্রশ্ন: ${getActiveQuestionPool().length}টি ` +
                `(বিল্ট-ইন ২৫০টি${deletedCount ? ' থেকে ' + deletedCount + 'টি বাদ' : ''}` +
                `${overrideCount ? ', ' + overrideCount + 'টি এডিট করা' : ''}, কাস্টম ${custom.length}টি)`;

            const pool = getActiveQuestionPool();
            const filtered = searchTerm
                ? pool.filter(item => item.q.toLowerCase().includes(searchTerm))
                : pool;
            const displayList = searchTerm ? filtered : filtered.slice(0, 60);

            box.innerHTML = '';
            box.appendChild(summaryDiv);

            if (!searchTerm && pool.length > 60) {
                const hint = document.createElement('div');
                hint.style.cssText = 'font-size:9px; color:#999; margin-bottom:4px;';
                hint.innerText = 'প্রথম ৬০টি দেখানো হচ্ছে — নির্দিষ্ট প্রশ্ন খুঁজতে উপরে সার্চ করুন।';
                box.appendChild(hint);
            }

            if (displayList.length === 0) {
                const empty = document.createElement('div');
                empty.style.cssText = 'font-size:10px; color:#999;';
                empty.innerText = 'কোনো প্রশ্ন পাওয়া যায়নি।';
                box.appendChild(empty);
                return;
            }

            const customTexts = new Set(custom.map(c => c.q));
            displayList.forEach(item => {
                const isCustom = customTexts.has(item.q);
                const idx = isCustom ? custom.findIndex(c => c.q === item.q) : -1;
                const shortText = item.q.length > 32 ? item.q.slice(0, 32) + '…' : item.q;

                const row = document.createElement('div');
                row.className = 'custom-q-item';

                const label = document.createElement('span');
                label.title = item.q; // ব্রাউজার নিজেই নিরাপদে এসকেপ করে
                label.innerText = (isCustom ? '🆕 ' : '') + shortText;

                const btnGroup = document.createElement('span');
                btnGroup.style.cssText = 'display:flex; gap:4px;';

                const editBtn = document.createElement('button');
                editBtn.style.background = '#2980b9';
                editBtn.innerText = 'এডিট';
                editBtn.addEventListener('click', () => {
                    if (isCustom) startEditQuestion('custom', idx);
                    else startEditQuestion('builtin', item.q);
                });

                const delBtn = document.createElement('button');
                delBtn.innerText = 'মুছুন';
                delBtn.addEventListener('click', () => {
                    if (isCustom) deleteCustomQuestion(idx);
                    else deleteBuiltinQuestion(item.q);
                });

                btnGroup.appendChild(editBtn);
                btnGroup.appendChild(delBtn);
                row.appendChild(label);
                row.appendChild(btnGroup);
                box.appendChild(row);
            });
        }



        // ===== AUDIO =====
        let audioCtx = null, isMuted = false;

        function initAudio() {
            if (!audioCtx) audioCtx = new(window.AudioContext || window.webkitAudioContext)();
        }

        function toggleAudio(event) {
            event.stopPropagation();
            isMuted = !isMuted;
            document.getElementById('audioBtn').innerText = isMuted ? '🔇' : '🔊';
        }

        function playSound(type) {
            if (!audioCtx || isMuted) return;
            const osc = audioCtx.createOscillator(), gain = audioCtx.createGain();
            osc.connect(gain);
            gain.connect(audioCtx.destination);
            if (type === 'correct') {
                osc.frequency.setValueAtTime(523.25, audioCtx.currentTime);
                osc.frequency.setValueAtTime(659.25, audioCtx.currentTime + 0.1);
                gain.gain.setValueAtTime(0.1, audioCtx.currentTime);
                osc.start();
                osc.stop(audioCtx.currentTime + 0.25);
            } else if (type === 'wrong') {
                osc.frequency.setValueAtTime(196.00, audioCtx.currentTime);
                osc.frequency.setValueAtTime(146.83, audioCtx.currentTime + 0.1);
                gain.gain.setValueAtTime(0.15, audioCtx.currentTime);
                osc.start();
                osc.stop(audioCtx.currentTime + 0.3);
            } else if (type === 'tick') {
                osc.frequency.setValueAtTime(880, audioCtx.currentTime);
                gain.gain.setValueAtTime(0.08, audioCtx.currentTime);
                gain.gain.exponentialRampToValueAtTime(0.001, audioCtx.currentTime + 0.1);
                osc.start();
                osc.stop(audioCtx.currentTime + 0.1);
            }
        }

        // ===== UI HELPERS =====
        function toggleMenu(event) {
            event.stopPropagation();
            document.getElementById('menuDropdown').classList.toggle('show');
        }

        function toggleTheme(event) {
            event.stopPropagation();
            document.body.classList.toggle('dark-mode');
            document.getElementById('themeBtn').innerText = document.body.classList.contains('dark-mode') ? '☀️' : '🌙';
        }

        function shareResult() {
            const { finalScore } = calculateFinalScore();
            const totalQ = quizQuestions.length || TOTAL_QUESTIONS_PER_ATTEMPT;
            const text = `আমি গাউসিয়া কমিটি বাংলাদেশের কুইজ কম্পিটিশনে ${finalScore}/${totalQ} স্কোর করেছি! 🏆\n✅ সঠিক: ${correctCount} | ❌ ভুল: ${wrongCount}\n\nযোগ দিন: ${window.location.href}`;
            if (navigator.share) navigator.share({ title: 'কুইজ', text });
            else window.open(`https://wa.me/?text=${encodeURIComponent(text)}`, '_blank');
        }

        // ===== 🖼️ স্কোর কার্ড ইমেজ তৈরি ও ডাউনলোড (ক্যানভাস, কোনো লাইব্রেরি ছাড়াই) =====
        function drawRoundedRect(ctx, x, y, w, h, r) {
            ctx.beginPath();
            ctx.moveTo(x + r, y);
            ctx.arcTo(x + w, y, x + w, y + h, r);
            ctx.arcTo(x + w, y + h, x, y + h, r);
            ctx.arcTo(x, y + h, x, y, r);
            ctx.arcTo(x, y, x + w, y, r);
            ctx.closePath();
        }

        function generateScoreCardCanvas() {
            const canvas = document.getElementById('renderCanvas');
            const W = 800, H = 1000;
            canvas.width = W;
            canvas.height = H;
            const ctx = canvas.getContext('2d');
            const font = "'Segoe UI', 'SolaimanLipi', sans-serif";

            // ব্যাকগ্রাউন্ড গ্রেডিয়েন্ট
            const grad = ctx.createLinearGradient(0, 0, W, H);
            grad.addColorStop(0, '#18661F');
            grad.addColorStop(0.5, '#1e3c72');
            grad.addColorStop(1, '#2a5298');
            ctx.fillStyle = grad;
            ctx.fillRect(0, 0, W, H);

            // সাদা কার্ড
            ctx.fillStyle = 'rgba(255,255,255,0.97)';
            drawRoundedRect(ctx, 40, 60, W - 80, H - 160, 30);
            ctx.fill();

            ctx.textAlign = 'center';

            // 🕌 আইকন
            ctx.font = '70px sans-serif';
            ctx.fillText('🕌', W / 2, 170);

            // কমিটির নাম
            ctx.fillStyle = '#18661F';
            ctx.font = `bold 28px ${font}`;
            ctx.fillText('গাউসিয়া কমিটি বাংলাদেশ', W / 2, 230);

            ctx.fillStyle = '#666';
            ctx.font = `16px ${font}`;
            ctx.fillText('ঘাষি মাঝির পাড়া ইউনিট', W / 2, 260);

            ctx.fillStyle = '#1e3c72';
            ctx.font = `bold 22px ${font}`;
            ctx.fillText('কুইজ কম্পিটিশন ২০২৬', W / 2, 300);

            // ট্রফি
            ctx.font = '90px sans-serif';
            ctx.fillText('🏆', W / 2, 420);

            // প্লেয়ারের নাম
            ctx.fillStyle = '#333';
            ctx.font = `bold 26px ${font}`;
            ctx.fillText(playerName || 'অংশগ্রহণকারী', W / 2, 480);

            // স্কোর
            const { finalScore, deduction } = calculateFinalScore();
            const totalQ = quizQuestions.length || TOTAL_QUESTIONS_PER_ATTEMPT;
            ctx.fillStyle = '#2ecc71';
            ctx.font = `bold 90px ${font}`;
            ctx.fillText(toBn(finalScore) + ' / ' + toBn(totalQ), W / 2, 600);

            ctx.fillStyle = '#666';
            ctx.font = `18px ${font}`;
            ctx.fillText(`✅ সঠিক: ${toBn(correctCount)}   ❌ ভুল: ${toBn(wrongCount)}   ➖ কাটা: ${toBn(deduction)}`, W / 2, 650);

            // তারিখ
            ctx.fillStyle = '#999';
            ctx.font = `14px ${font}`;
            const dateStr = new Date().toLocaleDateString('bn-BD');
            ctx.fillText('তারিখ: ' + dateStr, W / 2, 700);

            // ফুটার
            ctx.fillStyle = '#aaa';
            ctx.font = `12px ${font}`;
            ctx.fillText('ডেভেলপার: আসিফ হোসেন নুর', W / 2, H - 110);

            return canvas;
        }

        function downloadCanvasAsImage(canvas, filename) {
            canvas.toBlob(function(blob) {
                const url = URL.createObjectURL(blob);
                const a = document.createElement('a');
                a.href = url;
                a.download = filename;
                document.body.appendChild(a);
                a.click();
                a.remove();
                URL.revokeObjectURL(url);
            }, 'image/png');
        }

        function downloadScoreCard() {
            const canvas = generateScoreCardCanvas();
            downloadCanvasAsImage(canvas, 'quiz-score-card-' + (playerName || 'result') + '.png');
        }

        // ===== 🎓 সার্টিফিকেট তৈরি ও ডাউনলোড =====
        // ===== 🎨 ক্যানভাস ডিজাইন হেল্পার (তারকা ও গোলাকার সীল আঁকার জন্য) =====
        function drawStarPath(ctx, cx, cy, outerR, innerR, points) {
            ctx.beginPath();
            for (let i = 0; i < points * 2; i++) {
                const r = i % 2 === 0 ? outerR : innerR;
                const angle = (Math.PI / points) * i - Math.PI / 2;
                const x = cx + Math.cos(angle) * r;
                const y = cy + Math.sin(angle) * r;
                if (i === 0) ctx.moveTo(x, y); else ctx.lineTo(x, y);
            }
            ctx.closePath();
        }

        function drawCornerFlourish(ctx, x, y, size, quadrant, color) {
            // quadrant: 0=উপর-বাম, 1=উপর-ডান, 2=নিচ-ডান, 3=নিচ-বাম
            ctx.save();
            ctx.translate(x, y);
            ctx.rotate((Math.PI / 2) * quadrant);
            ctx.strokeStyle = color;
            ctx.lineWidth = 2.5;
            ctx.beginPath();
            ctx.arc(0, 0, size, 0, Math.PI / 2);
            ctx.stroke();
            ctx.beginPath();
            ctx.arc(0, 0, size * 0.7, 0, Math.PI / 2);
            ctx.stroke();
            ctx.beginPath();
            ctx.arc(size * 0.35, size * 0.35, size * 0.12, 0, Math.PI * 2);
            ctx.fillStyle = color;
            ctx.fill();
            ctx.restore();
        }

        function drawRoundRectPath(ctx, x, y, w, h, r) {
            ctx.beginPath();
            ctx.moveTo(x + r, y);
            ctx.arcTo(x + w, y, x + w, y + h, r);
            ctx.arcTo(x + w, y + h, x, y + h, r);
            ctx.arcTo(x, y + h, x, y, r);
            ctx.arcTo(x, y, x + w, y, r);
            ctx.closePath();
        }

        function generateCertificateCanvas(nameOverride, scoreOverride, totalOverride, onReady) {
            const template = getCertificateTemplate();
            const accentColor = template.color || '#18661F';
            const gold = '#d4af37';
            const canvas = document.getElementById('renderCanvas');
            const W = 1400, H = 990;
            canvas.width = W;
            canvas.height = H;
            const ctx = canvas.getContext('2d');
            const font = "'Segoe UI', 'SolaimanLipi', sans-serif";
            const serifFont = "'Georgia', 'Palatino Linotype', serif";

            // ===== 🎨 এলিগ্যান্ট গ্রেডিয়েন্ট ব্যাকগ্রাউন্ড =====
            const bgGrad = ctx.createLinearGradient(0, 0, W, H);
            bgGrad.addColorStop(0, '#fffdf6');
            bgGrad.addColorStop(0.5, '#fdf8ec');
            bgGrad.addColorStop(1, '#faf3dd');
            ctx.fillStyle = bgGrad;
            ctx.fillRect(0, 0, W, H);

            // হালকা ভিনিয়েট (কোণাগুলো সামান্য ছায়াযুক্ত করে গভীরতা আনা)
            const vignette = ctx.createRadialGradient(W / 2, H / 2, H / 3, W / 2, H / 2, H * 0.75);
            vignette.addColorStop(0, 'rgba(0,0,0,0)');
            vignette.addColorStop(1, 'rgba(0,0,0,0.06)');
            ctx.fillStyle = vignette;
            ctx.fillRect(0, 0, W, H);

            // ===== 🔒 Anti-copy watermark (তির্যক, হালকা, বারবার পুনরাবৃত্ত) =====
            ctx.save();
            ctx.globalAlpha = 0.045;
            ctx.fillStyle = accentColor;
            ctx.font = "bold 34px sans-serif";
            ctx.textAlign = 'center';
            ctx.translate(W / 2, H / 2);
            ctx.rotate(-Math.PI / 7);
            for (let y = -H; y < H; y += 90) {
                ctx.fillText('GAUSIA COMMITTEE BANGLADESH — QUIZ 2026', 0, y);
            }
            ctx.restore();

            // ===== 🖼️ অলঙ্কৃত ডাবল ফ্রেম =====
            const goldGrad = ctx.createLinearGradient(0, 0, W, H);
            goldGrad.addColorStop(0, '#f6e27a');
            goldGrad.addColorStop(0.5, gold);
            goldGrad.addColorStop(1, '#f6e27a');
            ctx.strokeStyle = goldGrad;
            ctx.lineWidth = 12;
            ctx.strokeRect(26, 26, W - 52, H - 52);
            ctx.strokeStyle = accentColor;
            ctx.lineWidth = 2;
            ctx.strokeRect(46, 46, W - 92, H - 92);
            ctx.strokeStyle = gold;
            ctx.lineWidth = 1;
            ctx.strokeRect(56, 56, W - 112, H - 112);

            // কোণার অলঙ্করণ (৪ কোণায়)
            drawCornerFlourish(ctx, 56, 56, 46, 0, gold);
            drawCornerFlourish(ctx, W - 56, 56, 46, 1, gold);
            drawCornerFlourish(ctx, W - 56, H - 56, 46, 2, gold);
            drawCornerFlourish(ctx, 56, H - 56, 46, 3, gold);

            ctx.textAlign = 'center';

            // ===== 🕌 লোগো (সোনালী রিং-বেষ্টিত) =====
            const logoY = 148;
            ctx.beginPath();
            ctx.arc(W / 2, logoY - 12, 52, 0, Math.PI * 2);
            ctx.strokeStyle = goldGrad;
            ctx.lineWidth = 4;
            ctx.stroke();
            ctx.font = '58px sans-serif';
            ctx.fillText(template.logoEmoji || '🕌', W / 2, logoY + 5);

            ctx.fillStyle = accentColor;
            ctx.font = `bold 25px ${font}`;
            ctx.fillText('গা উ সি য়া   ক মি টি   বা ং লা দে শ', W / 2, 235);
            ctx.font = `14px ${font}`;
            ctx.fillStyle = '#8a7a3f';
            ctx.fillText('ঘাষি মাঝির পাড়া ইউনিট', W / 2, 258);

            // ছোট অলংকৃত ডিভাইডার (হীরা-বিন্দু)
            function drawDivider(y, widthSpan) {
                ctx.strokeStyle = gold;
                ctx.lineWidth = 1.2;
                ctx.beginPath();
                ctx.moveTo(W / 2 - widthSpan, y);
                ctx.lineTo(W / 2 - 14, y);
                ctx.stroke();
                ctx.beginPath();
                ctx.moveTo(W / 2 + 14, y);
                ctx.lineTo(W / 2 + widthSpan, y);
                ctx.stroke();
                ctx.save();
                ctx.translate(W / 2, y);
                ctx.rotate(Math.PI / 4);
                ctx.fillStyle = gold;
                ctx.fillRect(-6, -6, 12, 12);
                ctx.restore();
            }
            drawDivider(280, 130);

            // ===== 🎗️ রিবন-স্টাইল টাইটেল ব্যানার =====
            const bannerY = 320, bannerH = 78, bannerW = 620;
            const bx = W / 2 - bannerW / 2;
            const ribbonGrad = ctx.createLinearGradient(bx, bannerY, bx + bannerW, bannerY);
            ribbonGrad.addColorStop(0, '#134515');
            ribbonGrad.addColorStop(0.5, accentColor);
            ribbonGrad.addColorStop(1, '#134515');
            ctx.beginPath();
            ctx.moveTo(bx, bannerY);
            ctx.lineTo(bx + bannerW, bannerY);
            ctx.lineTo(bx + bannerW - 18, bannerY + bannerH / 2);
            ctx.lineTo(bx + bannerW, bannerY + bannerH);
            ctx.lineTo(bx, bannerY + bannerH);
            ctx.lineTo(bx + 18, bannerY + bannerH / 2);
            ctx.closePath();
            ctx.fillStyle = ribbonGrad;
            ctx.fill();
            ctx.strokeStyle = gold;
            ctx.lineWidth = 1.5;
            ctx.stroke();

            ctx.fillStyle = '#fffdf0';
            ctx.font = `bold 34px ${font}`;
            ctx.fillText('অংশগ্রহণ সনদপত্র', W / 2, bannerY + 34);
            ctx.font = `italic 16px ${serifFont}`;
            ctx.fillStyle = '#f6e27a';
            ctx.fillText('C E R T I F I C A T E   O F   P A R T I C I P A T I O N', W / 2, bannerY + 58);

            // ===== 📜 মূল বিবরণ =====
            ctx.fillStyle = '#4a4a4a';
            ctx.font = `italic 20px ${serifFont}`;
            ctx.fillText('এই মর্মে সসম্মানে প্রত্যয়ন করা যাচ্ছে যে', W / 2, 452);

            const certName = nameOverride || playerName || 'অংশগ্রহণকারী';
            ctx.fillStyle = accentColor;
            ctx.font = `bold 50px ${serifFont}`;
            ctx.fillText(certName, W / 2, 522);

            // নামের নিচে অলংকৃত আন্ডারলাইন
            const nameWidth = Math.min(560, ctx.measureText(certName).width + 80);
            ctx.strokeStyle = goldGrad;
            ctx.lineWidth = 2;
            ctx.beginPath();
            ctx.moveTo(W / 2 - nameWidth / 2, 540);
            ctx.lineTo(W / 2 + nameWidth / 2, 540);
            ctx.stroke();

            ctx.fillStyle = '#4a4a4a';
            ctx.font = `20px ${font}`;
            ctx.fillText('"কুইজ কম্পিটিশন ২০২৬"-এ সফলভাবে ও সততার সাথে অংশগ্রহণ করেছেন।', W / 2, 585);

            const totalQ = totalOverride || quizQuestions.length || TOTAL_QUESTIONS_PER_ATTEMPT;
            let certScore = scoreOverride;
            if (certScore === undefined) certScore = calculateFinalScore().finalScore;

            // স্কোর — পিল-আকৃতির ব্যাজ
            const scoreText = 'প্রাপ্ত স্কোর: ' + toBn(certScore) + ' / ' + toBn(totalQ);
            ctx.font = `bold 24px ${font}`;
            const pillW = ctx.measureText(scoreText).width + 70;
            const pillH = 52, pillX = W / 2 - pillW / 2, pillY = 615;
            const pillGrad = ctx.createLinearGradient(pillX, pillY, pillX + pillW, pillY);
            pillGrad.addColorStop(0, '#e67e22');
            pillGrad.addColorStop(1, '#f39c12');
            drawRoundRectPath(ctx, pillX, pillY, pillW, pillH, pillH / 2);
            ctx.fillStyle = pillGrad;
            ctx.fill();
            ctx.strokeStyle = gold;
            ctx.lineWidth = 1.5;
            ctx.stroke();
            ctx.fillStyle = '#fff';
            ctx.fillText(scoreText, W / 2, pillY + 34);

            ctx.fillStyle = '#999';
            ctx.font = `15px ${font}`;
            ctx.fillText('তারিখ: ' + new Date().toLocaleDateString('bn-BD'), W / 2, 705);

            // ===== ✍️ স্বাক্ষর এলাকা =====
            ctx.strokeStyle = '#555';
            ctx.lineWidth = 1;
            ctx.beginPath();
            ctx.moveTo(W / 2 - 150, 800);
            ctx.lineTo(W / 2 + 150, 800);
            ctx.stroke();
            ctx.font = `italic 16px ${serifFont}`;
            ctx.fillStyle = '#555';
            ctx.fillText('আয়োজক কমিটির পক্ষে', W / 2, 825);

            // ===== 🏵️ সোনালী সীল/মেডেলিয়ন (নিচে-ডানে) =====
            const sealX = W - 155, sealY = H - 165, sealR = 62;
            const sealGrad = ctx.createRadialGradient(sealX, sealY, 5, sealX, sealY, sealR);
            sealGrad.addColorStop(0, '#fdf3c9');
            sealGrad.addColorStop(0.6, gold);
            sealGrad.addColorStop(1, '#a9821f');
            ctx.beginPath();
            ctx.arc(sealX, sealY, sealR, 0, Math.PI * 2);
            ctx.fillStyle = sealGrad;
            ctx.fill();
            ctx.strokeStyle = '#8a6d1f';
            ctx.lineWidth = 2;
            ctx.stroke();
            // রিবন-টেইল
            ctx.beginPath();
            ctx.moveTo(sealX - 22, sealY + sealR - 6);
            ctx.lineTo(sealX - 34, sealY + sealR + 46);
            ctx.lineTo(sealX - 8, sealY + sealR + 24);
            ctx.closePath();
            ctx.fillStyle = accentColor;
            ctx.fill();
            ctx.beginPath();
            ctx.moveTo(sealX + 22, sealY + sealR - 6);
            ctx.lineTo(sealX + 34, sealY + sealR + 46);
            ctx.lineTo(sealX + 8, sealY + sealR + 24);
            ctx.closePath();
            ctx.fill();
            // ভেতরের তারকা
            drawStarPath(ctx, sealX, sealY, sealR * 0.62, sealR * 0.28, 5);
            ctx.fillStyle = '#fffdf0';
            ctx.fill();
            ctx.strokeStyle = '#8a6d1f';
            ctx.lineWidth = 1;
            ctx.stroke();
            ctx.font = `bold 10px ${font}`;
            ctx.fillStyle = '#6b5416';
            ctx.fillText('VERIFIED', sealX, sealY + 4);

            // ===== 🆔 ইউনিক সার্টিফিকেট আইডি + সিরিয়াল নম্বর (যাচাইয়ের জন্য, অ্যাডমিন প্যানেলে সার্চযোগ্য) =====
            const certSerial = getNextCertSerial();
            const certId = generateCertId();
            saveCertificateRecord(certId, {
                name: certName,
                score: certScore,
                total: totalQ,
                serial: certSerial,
                date: new Date().toISOString()
            });

            // আইডি প্যানেল (নিচে-বামে, QR-এর পাশে)
            drawRoundRectPath(ctx, 70, H - 200, 260, 130, 10);
            ctx.fillStyle = 'rgba(255,255,255,0.6)';
            ctx.fill();
            ctx.strokeStyle = '#ddd';
            ctx.lineWidth = 1;
            ctx.stroke();

            ctx.textAlign = 'left';
            ctx.font = `bold 15px ${font}`;
            ctx.fillStyle = accentColor;
            ctx.fillText('সনদ নম্বর:', 84, H - 172);
            ctx.font = `bold 15px ${font}`;
            ctx.fillStyle = '#333';
            ctx.fillText(certSerial, 84, H - 150);

            ctx.font = `12px ${font}`;
            ctx.fillStyle = '#777';
            ctx.fillText('Certificate ID:', 84, H - 122);
            ctx.font = `11px ${font}`;
            ctx.fillText(certId, 84, H - 104);
            ctx.fillText('অ্যাডমিন প্যানেলে যাচাইযোগ্য', 84, H - 86);

            ctx.textAlign = 'center';
            ctx.font = `12px ${font}`;
            ctx.fillStyle = '#aaa';
            ctx.fillText('ডেভেলপার: আসিফ হোসেন নুর', W / 2, H - 30);

            // ===== 📱 QR কোড (certId এনকোড করা — নোট: এটা একটা অনলাইন যাচাই সার্ভার না, ম্যানুয়াল অ্যাডমিন-চেকের জন্য) =====
            if (window.QRCode && window.QRCode.toCanvas) {
                const qrCanvas = document.createElement('canvas');
                QRCode.toCanvas(qrCanvas, certId, { width: 130, margin: 1, color: { dark: accentColor, light: '#ffffffff' } }, function(err) {
                    if (!err) {
                        ctx.drawImage(qrCanvas, W - 200, H - 200, 130, 130);
                        ctx.strokeStyle = '#ccc';
                        ctx.lineWidth = 1;
                        ctx.strokeRect(W - 200, H - 200, 130, 130);
                    }
                    if (onReady) onReady(canvas, certId);
                });
            } else {
                if (onReady) onReady(canvas, certId);
            }

            return canvas;
        }

        function downloadCertificate() {
            generateCertificateCanvas(null, undefined, undefined, function(canvas) {
                downloadCanvasAsImage(canvas, 'quiz-certificate-' + (playerName || 'participant') + '.png');
            });
        }

        // ===== অ্যাডমিন থেকে যেকোনো নাম/স্কোরের জন্য সার্টিফিকেট বানানো (বিজয়ীদের জন্য) =====
        function adminGenerateCertificateFor(name, score, total) {
            generateCertificateCanvas(name, score, total || TOTAL_QUESTIONS_PER_ATTEMPT, function(canvas) {
                downloadCanvasAsImage(canvas, 'certificate-' + name + '.png');
            });
        }

        // ===== 🔎 সার্টিফিকেট আইডি দিয়ে যাচাই (অ্যাডমিন প্যানেল) =====
        function verifyCertificateById() {
            const id = prompt('🔎 সার্টিফিকেট আইডি লিখুন (যেমন GC-XXXXXXX-XXXXX):');
            if (!id) return;
            const records = getCertificateRecords();
            const rec = records[id.trim()];
            if (!rec) {
                alert('❌ এই আইডি দিয়ে কোনো সার্টিফিকেট পাওয়া যায়নি। এই ডিভাইসে ইস্যু করা না হলে যাচাই সম্ভব নয় (কোনো কেন্দ্রীয় সার্ভার নেই)।');
                return;
            }
            alert(`✅ বৈধ সার্টিফিকেট!\n\nনাম: ${rec.name}\nসনদ নম্বর: ${rec.serial || 'N/A'}\nস্কোর: ${rec.score}/${rec.total}\nইস্যুর তারিখ: ${new Date(rec.date).toLocaleString('bn-BD')}`);
        }

        // ===== ডেভেলপার পরিচিতি ও গাউসিয়া কমিটি সম্পর্কে (৩-ডট মেনু) =====
        function showDeveloperInfo() {
            alert(
`👨‍💻 ডেভেলপার পরিচিতি

নাম: আসিফ হোসেন নুর
পরিচয়: গাউসিয়া কমিটি বাংলাদেশ কুইজ কম্পিটিশন অ্যাপের ডেভেলপার
কাজ: অ্যাপ ডিজাইন, প্রশ্নব্যাংক, লাইফলাইন সিস্টেম ও নিরাপত্তা ব্যবস্থাপনা তৈরি

আপনার মতামত বা পরামর্শ থাকলে কমিটির মাধ্যমে জানাতে পারেন।
জাযাকাল্লাহু খইরন। 🤲`
            );
        }

        function showAboutCommittee() {
            alert(
`🕌 গাউসিয়া কমিটি বাংলাদেশ

ইউনিট: ঘাষি মাঝির পাড়া ইউনিট
উদ্দেশ্য: দ্বীনি শিক্ষা প্রসার ও ইসলামিক জ্ঞানচর্চাকে উৎসাহিত করা।
এই কুইজ কম্পিটিশন যুব সমাজের মাঝে ইসলামিক জ্ঞান বৃদ্ধির লক্ষ্যে আয়োজিত।

📅 বিজয়ী ঘোষণা: শনিবার, ২০ জুন ২০২৬ | সন্ধ্যা ৭:০০ টা
🏆 পুরস্কার: ১ম ৳৫,০০০ | ২য় ৳৩,০০০ | ৩য় ৳২,০০০

দোয়ায় সবাইকে স্মরণ রাখবেন। 🤲`
            );
        }

        // ===== FAQ / যোগাযোগ / Privacy / Terms / AI শর্টকাট =====
        function showFAQ() {
            alert(
`❓ প্রায়শই জিজ্ঞাসিত প্রশ্ন (FAQ)

১) কিভাবে খেলবো?
এন্ট্রি কোড ভেরিফাই করুন, নাম ও মোবাইল দিয়ে "কুইজ শুরু করুন"-এ ক্লিক করুন।

২) কত নম্বর পেলে ভালো হবে?
১০০-এর মধ্যে যত বেশি সম্ভব, বিশেষত ৮০+ স্কোর চমৎকার ফলাফল।

৩) Mystery Box কী?
টানা ১০টি সঠিক উত্তরে একটি র‍্যান্ডম রিওয়ার্ড বক্স পাবেন।

৪) Lifeline কী?
৫০:৫০, টাইম বোনাস, সঠিক উত্তর, অডিয়েন্স পোল ও লাইফ গার্ড — সাহায্যের জন্য ব্যবহার করা যায়।

৫) Timer কিভাবে কাজ করে?
অ্যাডমিন নির্ধারিত মোট সময় থেকে প্রতি সেকেন্ডে কমতে থাকে; সঠিক উত্তরে +৫ সে. ও ভুলে -৫ সে.।

৬) Result কোথায় দেখবো?
কুইজ শেষে সাথে সাথে স্ক্রিনে দেখাবে এবং চূড়ান্ত বিজয়ী কমিটির অনুষ্ঠানে ঘোষণা করা হবে।

আরও জিজ্ঞাসা থাকলে হোমপেজের 🤖 AI নিয়ম সহকারীতে লিখুন।`
            );
        }

        function showContact() {
            alert(
`📞 যোগাযোগ

গাউসিয়া কমিটি বাংলাদেশ
ঘাষি মাঝির পাড়া ইউনিট

কুইজ সংক্রান্ত যেকোনো জিজ্ঞাসা বা সমস্যার জন্য কমিটির স্থানীয় প্রতিনিধির সাথে সরাসরি যোগাযোগ করুন।`
            );
        }

        function showPrivacyPolicy() {
            alert(
`🔒 Privacy Policy (গোপনীয়তা নীতি)

• অংশগ্রহণের জন্য সংগৃহীত নাম ও মোবাইল নম্বর শুধুমাত্র প্রতিযোগিতা পরিচালনা ও ফলাফল যাচাইয়ের কাজে ব্যবহৃত হবে।
• তথ্য কোনো তৃতীয় পক্ষের কাছে বিক্রি বা শেয়ার করা হবে না।
• তথ্য ব্রাউজারের লোকাল স্টোরেজে এবং (সংযুক্ত থাকলে) কমিটির শিটে সংরক্ষিত হয়।
• কোনো তথ্য মুছে ফেলতে চাইলে কমিটির সাথে যোগাযোগ করুন।`
            );
        }

        function showTerms() {
            alert(
`📜 Terms & Conditions (শর্তাবলী)

• এন্ট্রি কোড ছাড়া অংশগ্রহণ করা যাবে না এবং প্রতিটি কোড একবারই ব্যবহারযোগ্য।
• প্রতিটি মোবাইল নম্বর ও ডিভাইস থেকে একবারই অংশগ্রহণ করা যাবে।
• অসৎ উপায়ে উত্তর খোঁজা বা নিয়ম ভঙ্গ করলে অংশগ্রহণ বাতিল বলে গণ্য হবে।
• পুরস্কার ও ফলাফল সংক্রান্ত সব সিদ্ধান্ত আয়োজক কমিটির — যা চূড়ান্ত ও অপরিবর্তনযোগ্য।
• এই অ্যাপ ব্যবহারের মাধ্যমে আপনি উপরোক্ত শর্তাবলীতে সম্মত হচ্ছেন বলে গণ্য হবে।`
            );
        }

        function focusAiAssistant() {
            const el = document.getElementById('aiQuestionInput');
            if (el) {
                el.scrollIntoView({ behavior: 'smooth', block: 'center' });
                el.focus();
            }
        }

        function showPrizeDetails() {
            alert(
`🏆 পুরস্কারের বিবরণ

🥇 ১ম স্থান: ৳৫,০০০
🥈 ২য় স্থান: ৳৩,০০০
🥉 ৩য় স্থান: ৳২,০০০

📅 বিজয়ী ঘোষণা ও পুরস্কার বিতরণ: শনিবার, ২০ জুন ২০২৬ | সন্ধ্যা ৭:০০ টা
📍 স্থান: কমিটির নির্ধারিত অনুষ্ঠানস্থল (স্থানীয় প্রতিনিধির কাছ থেকে জেনে নিন)

সর্বোচ্চ স্কোরের ভিত্তিতে বিজয়ী নির্ধারণ করা হবে।`
            );
        }

        function showSchedule() {
            const schedule = getCompetitionSchedule();
            if (schedule) {
                const start = new Date(schedule.start).toLocaleString('bn-BD');
                const end = new Date(schedule.end).toLocaleString('bn-BD');
                alert(`📅 প্রতিযোগিতার সময়সূচি\n\nশুরু: ${start}\nশেষ: ${end}\n\n🏅 বিজয়ী ঘোষণা: শনিবার, ২০ জুন ২০২৬ | সন্ধ্যা ৭:০০ টা`);
            } else {
                alert('📅 প্রতিযোগিতার সময়সূচি\n\nবর্তমানে অ্যাডমিন কর্তৃক ম্যানুয়ালি নিয়ন্ত্রিত হচ্ছে। হোমপেজে "প্রতিযোগিতা চালু আছে" নির্দেশনা দেখুন।\n\n🏅 বিজয়ী ঘোষণা: শনিবার, ২০ জুন ২০২৬ | সন্ধ্যা ৭:০০ টা');
            }
        }

        function shareCompetition() {
            const text = '🕌 গাউসিয়া কমিটি বাংলাদেশ কুইজ কম্পিটিশন ২০২৬-এ অংশ নিন! 🏆 পুরস্কার জিতুন।\n' + window.location.href;
            if (navigator.share) {
                navigator.share({ title: 'গাউসিয়া কমিটি কুইজ কম্পিটিশন', text: text });
            } else {
                window.open('https://wa.me/?text=' + encodeURIComponent(text), '_blank');
            }
        }

        function downloadRules() {
            const mins = Math.round(getQuizDuration() / 60);
            const content =
`গাউসিয়া কমিটি বাংলাদেশ - কুইজ কম্পিটিশন ২০২৬ - নিয়মাবলী
ঘাষি মাঝির পাড়া ইউনিট

১. অংশগ্রহণের শর্ত:
- বৈধ এন্ট্রি কোড আবশ্যক, প্রতিটি কোড একবার ব্যবহারযোগ্য।
- প্রতিটি মোবাইল নম্বর ও ডিভাইস থেকে একবারই অংশগ্রহণ করা যাবে।

২. প্রশ্ন ও সময়:
- মোট ২৫০টি প্রশ্নের ব্যাংক থেকে প্রতিবার ১০০টি প্রশ্ন এলোমেলোভাবে আসবে, পুনরাবৃত্তি ছাড়া।
- মোট সময়সীমা: ${mins} মিনিট।

৩. স্কোরিং:
- সঠিক উত্তরে +১ পয়েন্ট ও +৫ সেকেন্ড। ভুল উত্তরে -৫ সেকেন্ড। প্রতি ৪ ভুলে -১ পয়েন্ট কাটা হয়।

৪. লাইফলাইন: ৫০:৫০, +৩০ সেকেন্ড, সঠিক উত্তর, অডিয়েন্স পোল, লাইফ গার্ড।

৫. মিস্টারি বক্স: টানা ১০ সঠিক উত্তরে র‍্যান্ডম রিওয়ার্ড।

৬. সততা নীতি: অসৎ উপায়ে উত্তর খোঁজা নিষিদ্ধ। রাইট-ক্লিক/কপি-পেস্ট/ডেভেলপার টুলস বন্ধ থাকবে ও বারবার ট্যাব পরিবর্তনে অটো-সাবমিট হবে।

৭. পুরস্কার: ১ম ৳৫,০০০ | ২য় ৳৩,০০০ | ৩য় ৳২,০০০
বিজয়ী ঘোষণা: শনিবার, ২০ জুন ২০২৬ | সন্ধ্যা ৭:০০ টা

আল্লাহ আপনাদের সহায় হোন।`;
            const blob = new Blob([content], { type: 'text/plain;charset=utf-8;' });
            const url = URL.createObjectURL(blob);
            const a = document.createElement('a');
            a.href = url;
            a.download = 'গাউসিয়া-কুইজ-নিয়মাবলী.txt';
            document.body.appendChild(a);
            a.click();
            a.remove();
            URL.revokeObjectURL(url);
        }

        // ===== কম্পিটিশনের নিয়মাবলী =====
        function showRules() {
            const mins = Math.round(getQuizDuration() / 60);
            const rules = `
📋 **গাউসিয়া কমিটি কুইজ কম্পিটিশন ২০২৬ - নিয়মাবলী**

📌 **১. অংশগ্রহণের শর্ত:**
• শুধুমাত্র বৈধ এন্ট্রি কোডধারী ব্যক্তিরা অংশ নিতে পারবেন।
• প্রতিটি মোবাইল নম্বর ও প্রতিটি ডিভাইস থেকে শুধুমাত্র একবার অংশগ্রহণ করা যাবে।

📌 **২. প্রশ্ন ও সময়সীমা:**
• মোট প্রশ্নব্যাংকে ২৫০টি প্রশ্ন আছে; প্রতিটি অংশগ্রহণে এলোমেলোভাবে বাছাই করা ১০০টি প্রশ্ন আসবে।
• একই খেলায় কোনো প্রশ্ন কখনোই দুইবার আসবে না।
• সম্পূর্ণ কুইজের জন্য সময়সীমা: ${mins} মিনিট (অ্যাডমিন কর্তৃক নির্ধারিত)।
• সময় শেষ হলে স্বয়ংক্রিয়ভাবে ফলাফল দেখাবে।

📌 **৩. স্কোরিং:**
• প্রতিটি সঠিক উত্তরের জন্য +১ পয়েন্ট (এবং +৫ সেকেন্ড সময় বোনাস)।
• প্রতিটি ভুল উত্তরে -৫ সেকেন্ড সময় কাটা হবে।
• প্রতি ৪টি ভুল উত্তরের জন্য -১ পয়েন্ট কাটা হবে।
• টানা ১০টি সঠিক উত্তর দিলে 'মিস্টারি বক্স' পাবেন।

📌 **৪. লাইফলাইন:**
• 💡 ৫০:৫০, ⏱️ +৩০ সেকেন্ড, 🎯 সঠিক উত্তর, 👥 অডিয়েন্স পোল, 🛡️ লাইফ গার্ড — প্রতিটি একবার ব্যবহারযোগ্য।

📌 **৫. মিস্টারি বক্স রিওয়ার্ড:**
• 🛡️ লাইফ গার্ড, ⏱️ সময় বোনাস, 🎯 ফ্রি স্কোর, 🔥 ডাবল স্কোর, ⏭️ স্কিপ প্রশ্ন, 💡 হিন্ট, 🎁 লাইফলাইন রিস্টোর।

📌 **৬. সততা ও নিরাপত্তা নীতি (কঠোরভাবে প্রযোজ্য):**
⚠️ **চুরি করলে আল্লাহ কাছে দায়বদ্ধ থাকবেন।**
• কোনো অসৎ উপায়ে উত্তর খোঁজা, স্ক্রিনশট শেয়ার, বা অন্যের সাহায্য নেওয়া সম্পূর্ণ নিষিদ্ধ।
• কুইজ চলাকালীন রাইট-ক্লিক, কপি-পেস্ট, টেক্সট সিলেকশন ও ডেভেলপার টুলস ব্যবহার নিষ্ক্রিয় রাখা হয়েছে।
• কুইজ চলাকালীন ট্যাব পরিবর্তন/মিনিমাইজ করলে সতর্কতা দেওয়া হবে; বারবার করলে কুইজ স্বয়ংক্রিয়ভাবে জমা হয়ে যাবে।
• একই মোবাইল নম্বর বা একই ডিভাইস দিয়ে একাধিকবার অংশগ্রহণ করা যাবে না।
• নিয়ম ভঙ্গ করলে অংশগ্রহণ বাতিল বলে গণ্য হবে।

📌 **৭. পুরস্কার:**
🥇 ১ম স্থান: ৳৫,০০০ | 🥈 ২য় স্থান: ৳৩,০০০ | 🥉 ৩য় স্থান: ৳২,০০০

📅 **বিজয়ী ঘোষণা:** শনিবার, ২০ জুন ২০২৬ | সন্ধ্যা ৭:০০ টা

💪 **শুভকামনা! আল্লাহ আপনাদের সহায় হোন।**
            `;

            alert(rules);
        }

        // ===== 🤖 AI নিয়ম সহকারী (রুল-বেসড লোকাল অ্যাসিস্ট্যান্ট, কোনো ইন্টারনেট/API লাগে না) =====
        const AI_FAQ = [
            { keys: ['এন্ট্রি কোড', 'কোড', 'ভেরিফাই'], ans: 'এন্ট্রি কোড ছাড়া অংশগ্রহণ করা যায় না। কমিটির কাছ থেকে কোড সংগ্রহ করে "কোড দিন" বক্সে লিখে ভেরিফাই বাটনে ক্লিক করুন। প্রতিটি কোড শুধু ১ বার ব্যবহার করা যাবে।' },
            { keys: ['সময়', 'টাইমার', 'মিনিট', 'সেকেন্ড'], ans: 'সম্পূর্ণ ১০০টি প্রশ্নের জন্য একটি নির্দিষ্ট সময়সীমা থাকে, যা অ্যাডমিন প্যানেল থেকে নির্ধারণ করা হয়। হোমপেজে বর্তমান সময়সীমা দেখতে পাবেন। প্রতিটি সঠিক উত্তরে +৫ সেকেন্ড ও ভুল উত্তরে -৫ সেকেন্ড হয়।' },
            { keys: ['প্রশ্ন', 'কতটা প্রশ্ন', '১০০'], ans: 'মোট প্রশ্নব্যাংকে ২৫০টি প্রশ্ন আছে। প্রতিবার অংশগ্রহণে এলোমেলোভাবে বাছাইকৃত ১০০টি প্রশ্ন আসবে এবং একই খেলায় কোনো প্রশ্ন দুইবার আসবে না।' },
            { keys: ['পুরস্কার', 'প্রাইজ', 'টাকা'], ans: '১ম স্থান ৳৫,০০০, ২য় স্থান ৳৩,০০০ এবং ৩য় স্থান ৳২,০০০ পুরস্কার থাকছে। বিজয়ী ঘোষণা হবে শনিবার, ২০ জুন ২০২৬, সন্ধ্যা ৭:০০ টায়।' },
            { keys: ['লাইফলাইন'], ans: 'লাইফলাইনগুলো হলো: ৫০:৫০, +৩০ সেকেন্ড, সঠিক উত্তর, অডিয়েন্স পোল ও লাইফ গার্ড — প্রতিটি একবার করে ব্যবহার করা যাবে।' },
            { keys: ['মিস্টারি বক্স', 'বক্স'], ans: 'টানা ১০টি প্রশ্নের সঠিক উত্তর দিলে একটি মিস্টারি বক্স খোলার সুযোগ পাবেন, যেখানে টাইম বোনাস, ফ্রি স্কোর, ডাবল স্কোর, স্কিপ, হিন্ট ইত্যাদি র‍্যান্ডম রিওয়ার্ড পাওয়া যায়।' },
            { keys: ['স্কোর', 'নাম্বার', 'নম্বর'], ans: 'প্রতিটি সঠিক উত্তরে +১ পয়েন্ট। প্রতি ৪টি ভুল উত্তরের জন্য ১ পয়েন্ট কাটা যায়। চূড়ান্ত স্কোর হলো (সঠিক উত্তর - কর্তনকৃত পয়েন্ট)।' },
            { keys: ['চুরি', 'নকল', 'অসৎ', 'গুগল', 'সার্চ'], ans: 'কোনো অসৎ উপায়ে উত্তর খোঁজা সম্পূর্ণ নিষিদ্ধ। কুইজ চলাকালীন রাইট-ক্লিক, কপি-পেস্ট ও ডেভেলপার টুলস বন্ধ রাখা হয়েছে এবং ট্যাব পরিবর্তন করলে সতর্কতা/স্বয়ংক্রিয় জমা হতে পারে।' },
            { keys: ['একাধিকবার', 'দুইবার', 'আবার অংশগ্রহণ'], ans: 'না, প্রতিটি মোবাইল নম্বর ও প্রতিটি ডিভাইস থেকে শুধুমাত্র একবারই অংশগ্রহণ করা যাবে।' },
            { keys: ['নিবন্ধন', 'রেজিস্ট্রেশন', 'নাম', 'মোবাইল'], ans: 'এন্ট্রি কোড ভেরিফাই করার পর আপনার নাম ও সঠিক ১১ ডিজিটের মোবাইল নম্বর দিয়ে "কুইজ শুরু করুন" বাটনে ক্লিক করলেই নিবন্ধন সম্পন্ন হবে।' }
        ];

        function askAiAssistant() {
            const input = document.getElementById('aiQuestionInput');
            const q = input.value.trim();
            if (!q) return;
            renderAiMessage(q, true);
            input.value = '';

            let matched = null;
            for (const item of AI_FAQ) {
                if (item.keys.some(k => q.includes(k))) { matched = item; break; }
            }

            const answer = matched
                ? matched.ans
                : 'দুঃখিত, এই বিষয়ে সরাসরি তথ্য নেই। অনুগ্রহ করে "📋 কম্পিটিশনের নিয়মাবলী" মেনু থেকে সম্পূর্ণ নিয়ম দেখুন, অথবা এন্ট্রি কোড, সময়সীমা, পুরস্কার, লাইফলাইন বা স্কোরিং নিয়ে জিজ্ঞাসা করুন।';

            setTimeout(() => renderAiMessage(answer, false), 300);
        }

        function renderAiMessage(text, isUser) {
            const box = document.getElementById('aiChatBox');
            const bubble = document.createElement('div');
            bubble.style.cssText = isUser
                ? 'align-self:flex-end; background:var(--primary); color:#fff; padding:7px 11px; border-radius:12px 12px 2px 12px; font-size:12px; max-width:85%; margin-bottom:6px;'
                : 'align-self:flex-start; background:#eef4ee; color:#222; padding:7px 11px; border-radius:12px 12px 12px 2px; font-size:12px; max-width:85%; margin-bottom:6px;';
            bubble.innerText = (isUser ? '🧑 ' : '🤖 ') + text;
            box.appendChild(bubble);
            box.scrollTop = box.scrollHeight;
        }

        // ===== 🔒 অ্যান্টি-চিটিং / সিকিউরিটি মোড =====
        let tabSwitchCount = 0;
        const MAX_TAB_SWITCH_WARNINGS = 3;

        function blockContextMenu(e) { e.preventDefault(); return false; }
        function blockCopyPaste(e) { e.preventDefault(); return false; }

        function blockCheatKeys(e) {
            // F12, Ctrl+Shift+I/J/C, Ctrl+U, Ctrl+S, Ctrl+P
            const key = e.key ? e.key.toLowerCase() : '';
            if (
                e.key === 'F12' ||
                (e.ctrlKey && e.shiftKey && ['i', 'j', 'c'].includes(key)) ||
                (e.ctrlKey && ['u', 's', 'p'].includes(key)) ||
                (e.metaKey && e.altKey && ['i', 'j', 'c'].includes(key))
            ) {
                e.preventDefault();
                if (quizActive) {
                    tabSwitchCount++;
                    handleSecurityViolation('ডেভেলপার টুলস/শর্টকাট ব্যবহারের চেষ্টা সনাক্ত হয়েছে।');
                }
                return false;
            }
        }

        function handleVisibilityChange() {
            if (!quizActive) return;
            if (document.hidden) {
                tabSwitchCount++;
                handleSecurityViolation('আপনি অন্য ট্যাব/অ্যাপে গিয়েছিলেন।');
            }
        }

        function handleSecurityViolation(reason) {
            if (!quizActive) return;
            addCheatLog(reason);
            if (tabSwitchCount >= MAX_TAB_SWITCH_WARNINGS) {
                alert('⚠️ বারবার নিয়ম লঙ্ঘনের কারণে আপনার কুইজ স্বয়ংক্রিয়ভাবে জমা দেওয়া হলো।');
                showFinalResult();
            } else {
                alert(`⚠️ সতর্কতা (${tabSwitchCount}/${MAX_TAB_SWITCH_WARNINGS}): ${reason}\nপুনরায় করলে কুইজ স্বয়ংক্রিয়ভাবে জমা হয়ে যাবে!`);
            }
        }

        function blockBackNavigation() {
            history.pushState(null, '', window.location.href);
        }

        // ===== মাল্টি-ট্যাব/উইন্ডো সনাক্তকরণ (localStorage 'storage' ইভেন্ট ভিত্তিক) =====
        let quizSessionId = null;

        function handleStorageEvent(e) {
            if (!quizActive) return;
            if (e.key === 'mp_activeSession' && e.newValue && e.newValue !== quizSessionId) {
                tabSwitchCount++;
                handleSecurityViolation('অন্য একটি ট্যাব/উইন্ডোতে কুইজ চালু করার চেষ্টা সনাক্ত হয়েছে।');
            }
        }

        function handleBeforeUnload(e) {
            if (!quizActive) return;
            addCheatLog('পেজ রিফ্রেশ/বন্ধ করার চেষ্টা হয়েছিল।');
            e.preventDefault();
            e.returnValue = 'কুইজ চলাকালীন পেজ ছাড়লে আপনার অগ্রগতি হারাতে পারেন। আপনি কি নিশ্চিত?';
            return e.returnValue;
        }

        function enterQuizSecurityMode() {
            tabSwitchCount = 0;
            quizSessionId = Date.now() + '-' + Math.random().toString(36).slice(2);
            localStorage.setItem('mp_activeSession', quizSessionId);
            document.addEventListener('contextmenu', blockContextMenu);
            document.addEventListener('copy', blockCopyPaste);
            document.addEventListener('cut', blockCopyPaste);
            document.addEventListener('paste', blockCopyPaste);
            document.addEventListener('keydown', blockCheatKeys);
            document.addEventListener('visibilitychange', handleVisibilityChange);
            window.addEventListener('blur', handleVisibilityChange);
            window.addEventListener('storage', handleStorageEvent);
            window.addEventListener('beforeunload', handleBeforeUnload);
            history.pushState(null, '', window.location.href);
            window.addEventListener('popstate', blockBackNavigation);
        }

        function exitQuizSecurityMode() {
            document.removeEventListener('contextmenu', blockContextMenu);
            document.removeEventListener('copy', blockCopyPaste);
            document.removeEventListener('cut', blockCopyPaste);
            document.removeEventListener('paste', blockCopyPaste);
            document.removeEventListener('keydown', blockCheatKeys);
            document.removeEventListener('visibilitychange', handleVisibilityChange);
            window.removeEventListener('blur', handleVisibilityChange);
            window.removeEventListener('popstate', blockBackNavigation);
            window.removeEventListener('storage', handleStorageEvent);
            window.removeEventListener('beforeunload', handleBeforeUnload);
        }


        // ===== INIT =====
        window.onload = function() {
            setTimeout(() => {
                const splash = document.getElementById('splashScreen');
                if (splash) {
                    splash.style.opacity = '0';
                    setTimeout(() => splash.remove(), 500);
                }
            }, 1100);

            isCompetitionActive = getCompetitionStatus();
            updateParticipantCount();
            updateAdminLeaderboard();
            updateHomeTimerDisplay();
            updateHallOfFameButtonVisibility();
            renderCountdown();
            syncCompetitionStatusFromBackend();

            setInterval(updateAdminLeaderboard, 3000);
            setInterval(updateParticipantCount, 5000);
            setInterval(renderCountdown, 1000);
            setInterval(syncCompetitionStatusFromBackend, 10000);

            if (isCompetitionActive) {
                document.getElementById('startBtn').disabled = true;
                document.getElementById('startBtn').innerText = '🔓 এন্ট্রি কোড দিন';
            }

            if (localStorage.getItem('mp_deviceParticipated') === 'true') {
                document.getElementById('startBtn').disabled = true;
                document.getElementById('startBtn').innerText = '✅ ইতিমধ্যে অংশগ্রহণ করা হয়েছে';
                document.getElementById('entrySection').style.display = 'none';
            }

            const aiInput = document.getElementById('aiQuestionInput');
            if (aiInput) {
                aiInput.addEventListener('keypress', function(e) {
                    if (e.key === 'Enter') askAiAssistant();
                });
            }

            const pledge = document.getElementById('honestyPledge');
            if (pledge) {
                pledge.addEventListener('change', updateStartButtonState);
            }

            // 🎫 QR কোড স্ক্যান করে আসা হলে URL থেকে কোড অটো-ফিল ও যাচাই করুন
            const urlCode = new URLSearchParams(window.location.search).get('code');
            if (urlCode) {
                const entryCodeInput = document.getElementById('entryCode');
                if (entryCodeInput) {
                    entryCodeInput.value = urlCode.toUpperCase();
                    verifyEntryCode();
                }
            }
        };

        // বাইরে ক্লিক করলে মেনু বন্ধ
        document.addEventListener('click', function() {
            document.getElementById('menuDropdown').classList.remove('show');
        });

        // সবসময় সক্রিয় বেসিক সুরক্ষা (রাইট-ক্লিক সবসময় বন্ধ)
        document.addEventListener('contextmenu', function(e) {
            e.preventDefault();
        });
    </script>
</body>
</html>
