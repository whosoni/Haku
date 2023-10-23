<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Digital Flower Blooming</title>
    <style>
        body {
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
            background-color: #87CEEB; /* Sky Blue background */
        }

        #pot {
            width: 100px;
            height: 150px;
            background-color: #8B4513; /* Saddle Brown for pot color */
            position: relative;
            border-radius: 10px 10px 0 0;
        }

        #flower {
            width: 80px;
            height: 80px;
            background-color: #FFD700; /* Gold for flower color */
            border-radius: 50%;
            position: absolute;
            top: 10px;
            left: 10px;
            animation: bloom 3s ease-in-out forwards;
        }

        @keyframes bloom {
            0% {
                width: 0;
                height: 0;
                top: 50px;
                left: 50px;
                background-color: #FFD700; /* Gold for initial color */
            }
            100% {
                width: 80px;
                height: 80px;
                top: 10px;
                left: 10px;
                background-color: #FF69B4; /* Hot Pink for bloomed color */
            }
        }
    </style>
</head>
<body>
    <div id="pot">
        <div id="flower"></div>
    </div>
</body>
</html>
