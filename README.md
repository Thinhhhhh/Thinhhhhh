<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chúc Mừng Valentine, Tí Hon!</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #ffebcd;
            text-align: center;
            padding: 20px;
            margin: 0;
            overflow: hidden;
        }

        h1 {
            color: #dc3545;
        }

        p {
            font-size: 18px;
            color: #721c24;
        }

        #heart-container {
            position: relative;
            width: 100%;
            height: 300px;
        }

        .heart {
            position: absolute;
            width: 52px;
            height: 48px;
            background: url('heart.png') no-repeat;
            background-size: contain;
            animation: float 1.5s infinite ease-in-out;
        }

        @keyframes float {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-20px);
            }
        }
    </style>
</head>
<body>
    <h1>Chúc Mừng Ngày Valentine, Tí Hon!</h1>
    <p>Em yêu, anh muốn nói rằng anh yêu em nhiều lắm! Chúc em có một ngày Valentine tràn đầy hạnh phúc và ấm áp.</p>
    
    <div id="heart-container">
        <div class="heart" style="top: 20%; left: 30%;"></div>
        <div class="heart" style="top: 50%; left: 50%;"></div>
        <div class="heart" style="top: 30%; left: 70%;"></div>
    </div>
</body>
</html>
