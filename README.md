<!DOCTYPE html>
<html>
<head>
    <title>Made By Rajasekar Babu</title>

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            margin: 0;
            background: black;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            animation: fadeIn 2s ease-in;
        }

        img {
            width: 60%;          /* 👈 medium size */
            max-width: 400px;    /* 👈 control size on PC */
            border-radius: 12px; /* 👈 smooth edges */
            
            /* subtle zoom effect */
            animation: zoom 8s ease-in-out infinite alternate;
        }

        @keyframes zoom {
            0% { transform: scale(1); }
            100% { transform: scale(1.05); }
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
    </style>
</head>

<body>

<img src="RB.jpg">

</body>
</html>
