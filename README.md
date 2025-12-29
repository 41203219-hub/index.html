<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>張恩愷的個人專案首頁</title>
    <style>
        /* 基本樣式設定 */
        body {
            font-family: "Microsoft JhengHei", Arial, sans-serif;
            background-color: #f4f7f6;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
        }

        /* 個人資訊區塊 */
        .header {
            text-align: center;
            margin-bottom: 40px;
        }

        .header h1 {
            font-size: 2.8rem;
            color: #2c3e50;
            margin: 0 0 10px 0;
        }

        .header p {
            font-size: 1.2rem;
            color: #7f8c8d;
            margin: 5px 0;
            letter-spacing: 1px;
        }

        /* 日期樣式 */
        .date-info {
            font-weight: bold;
            color: #34495e;
            background: #e1e8ed;
            padding: 5px 15px;
            border-radius: 20px;
            display: inline-block;
            margin-top: 10px;
        }

        /* 按鈕容器 */
        .button-group {
            display: flex;
            gap: 20px;
        }

        /* 按鈕通用樣式 */
        .btn {
            text-decoration: none;
            padding: 15px 35px;
            font-size: 1.1rem;
            font-weight: bold;
            color: white;
            border-radius: 50px;
            transition: all 0.3s ease;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        /* BMI 按鈕顏色 */
        .btn-bmi {
            background-color: #3498db;
        }

        /* 番茄鐘按鈕顏色 */
        .btn-tomato {
            background-color: #e74c3c;
        }

        /* 滑鼠懸停效果 */
        .btn:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 15px rgba(0,0,0,0.2);
            filter: brightness(1.1);
        }

        /* 手機版適應 */
        @media (max-width: 480px) {
            .button-group {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>

    <div class="header">
        <h1>張恩愷</h1>
        <p>學號：41203219</p>
        <div class="date-info">2025 / 12 / 22</div>
    </div>

    <div class="button-group">
        <a href="https://41203219-hub.github.io/BMI/" class="btn btn-bmi">BMI 計算機</a>
        
        <a href="https://41203219-hub.github.io/tomato-clock/" class="btn btn-tomato">番茄鐘計時器</a>
    </div>

</body>
</html>
