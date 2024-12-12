
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>نتائج مباريات كرة القدم</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            direction: rtl;
        }

        header {
            background-color: #0b6623;
            color: #fff;
            padding: 10px 20px;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #066b23;
            padding: 10px 0;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 0 20px;
        }

        .match-table {
            width: 100%;
            border-collapse: collapse;
            background: #fff;
            margin-bottom: 20px;
        }

        .match-table th, .match-table td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: center;
        }

        .match-table th {
            background-color: #0b6623;
            color: #fff;
        }

        .subscribe {
            text-align: center;
            margin-top: 20px;
        }

        .subscribe button {
            background-color: #0b6623;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            font-size: 18px;
            cursor: pointer;
        }

        .subscribe button:hover {
            background-color: #066b23;
        }
    </style>
</head>
<body>
    <header>
        <h1>نتائج مباريات كرة القدم اليومية</h1>
    </header>

    <nav>
        <a href="#">الرئيسية</a>
        <a href="#">المباريات</a>
        <a href="#">المراهنات</a>
        <a href="#">الاشتراكات</a>
        <a href="#">اتصل بنا</a>
    </nav>

    <div class="container">
        <h2>جدول المباريات اليوم</h2>
        <table class="match-table">
            <thead>
                <tr>
                    <th>الفريق الأول</th>
                    <th>الفريق الثاني</th>
                    <th>الوقت</th>
                    <th>النتيجة</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>ريال مدريد</td>
                    <td>برشلونة</td>
                    <td>21:00</td>
                    <td>1 - 2</td>
                </tr>
                <tr>
                    <td>ليفربول</td>
                    <td>مانشستر سيتي</td>
                    <td>18:30</td>
                    <td>3 - 3</td>
                </tr>
            </tbody>
        </table>

        <div class="subscribe">
            <h3>اشترك الآن للحصول على المزيد من الميزات</h3>
            <button>اشترك الآن</button>
        </div>
    </div>
</body>
</html>
