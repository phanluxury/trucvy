<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chúc Mừng Sinh Nhật!</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #ffccff;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            flex-direction: column;
        }

        h1 {
            color: #ff69b4;
            font-size: 3rem;
            text-align: center;
            margin-top: 0;
        }

        p {
            color: #333;
            font-size: 1.2rem;
            text-align: center;
            margin: 10px 0;
        }

        .balloons {
            margin-top: 20px;
        }

        .balloon {
            width: 100px;
            height: 150px;
            background-color: #ff6347;
            border-radius: 50%;
            margin: 10px;
            display: inline-block;
            position: relative;
            animation: float 3s ease-in-out infinite;
        }

        .balloon:nth-child(odd) {
            background-color: #ff1493;
        }

        .balloon:before {
            content: '';
            width: 10px;
            height: 50px;
            background-color: #000;
            position: absolute;
            bottom: -50px;
            left: 50%;
            transform: translateX(-50%);
        }

        @keyframes float {
            0% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-20px);
            }
            100% {
                transform: translateY(0);
            }
        }

        .message {
            font-size: 1.5rem;
            color: #ff4500;
            font-weight: bold;
            margin-top: 20px;
            text-align: center;
        }
    </style>
</head>
<body>

    <h1>Chúc Mừng Sinh Nhật!</h1>
    <p>Chúc bạn có một ngày sinh nhật thật vui vẻ và đầy ý nghĩa!</p>

    <div class="balloons">
        <div class="balloon"></div>
        <div class="balloon"></div>
        <div class="balloon"></div>
        <div class="balloon"></div>
        <div class="balloon"></div>
    </div>

    <div class="message">
        <p>Chúc bạn thêm tuổi mới, thêm nhiều niềm vui và hạnh phúc!</p>
    </div>

</body>
</html>
