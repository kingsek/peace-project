<!DOCTYPE html>
<html>
<head>
    <title>Made BY Rajasekar  Babu </title>

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            margin: 0;
            overflow: hidden;
            background: black;
        }

        img {
            width: 100%;
            height: 100vh;
            object-fit: cover;

            /* Smooth zoom effect */
            animation: zoom 10s ease-in-out infinite alternate;

            /* Slight dark filter for cinematic feel */
            filter: brightness(0.9) contrast(1.1);
        }

        @keyframes zoom {
            0% {
                transform: scale(1);
            }
            100% {
                transform: scale(1.1);
            }
        }

        /* Optional fade-in effect */
        body {
            animation: fadeIn 2s ease-in;
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
