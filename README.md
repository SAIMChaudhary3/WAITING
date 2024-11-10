html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Do you love me?</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #ffe4e1;
            font-family: 'Comic Sans MS', cursive, sans-serif;
            margin: 0;
            perspective: 1000px;
        }
        .container {
            text-align: center;
            background-color: #ffc0cb;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
            transform: rotateY(20deg);
            transition: transform 0.5s;
        }
        .container:hover {
            transform: rotateY(0deg);
        }
        .container h1 {
            color: #ff1493;
            font-size: 36px;
        }
        .container p {
            font-size: 20px;
            color: #ff69b4;
        }
        .button {
            background-color: #ff1493;
            color: #fff;
            padding: 15px 30px;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            font-size: 18px;
            margin-top: 20px;
        }
        .button:hover {
            background-color: #ff69b4;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Do You Also Love Me?</h1>
        <p>MY CREATIVITY ENDED HERE. You have no choice rather than yes</p>
        <button class="button" onclick="alert('She said YES!')">Yes</button>
    </div>
</body>
</html>
