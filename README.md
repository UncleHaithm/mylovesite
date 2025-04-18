# mylovesite
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>موقع الحب</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #fce4ec;
            font-family: 'Cairo', sans-serif;
        }
        .heart-container {
            text-align: center;
        }
        .heart {
            width: 100px;
            height: 100px;
            background-color: red;
            position: relative;
            transform: rotate(-45deg);
            margin: 0 auto 20px auto;
        }
        .heart::before,
        .heart::after {
            content: "";
            width: 100px;
            height: 100px;
            background-color: red;
            border-radius: 50%;
            position: absolute;
        }
        .heart::before {
            top: -50px;
            left: 0;
        }
        .heart::after {
            left: 50px;
            top: 0;
        }
        h1 {
            color: #880e4f;
            font-size: 2.5em;
        }
    </style>
</head>
<body>
    <div class="heart-container">
        <div class="heart"></div>
        <h1>إيلان</h1>
    </div>
</body>
</html>
