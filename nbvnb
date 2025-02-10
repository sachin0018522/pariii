<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cute Teddy Animation</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background-color: #ffe6e6;
        }
        .button {
            background-color: #ff99cc;
            border: none;
            padding: 10px 20px;
            font-size: 18px;
            color: white;
            border-radius: 20px;
            cursor: pointer;
            margin-bottom: 20px;
        }
        .teddy {
            width: 250px;
            height: 250px;
            stroke-dasharray: 1000;
            stroke-dashoffset: 1000;
            stroke: #704214;
            fill: none;
            animation: draw 3s linear forwards, fillColor 1s 3.2s forwards, dance 1s 4.2s infinite alternate ease-in-out;
            display: none;
        }
        @keyframes draw {
            to {
                stroke-dashoffset: 0;
            }
        }
        @keyframes fillColor {
            to {
                fill: #d19c6b;
            }
        }
        @keyframes dance {
            0% {
                transform: rotate(-5deg) translateY(0);
            }
            100% {
                transform: rotate(5deg) translateY(-5px);
            }
        }
        .message {
            display: none;
            font-size: 24px;
            color: #704214;
            margin-top: 20px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <button class="button" onclick="document.querySelector('.teddy').style.display='block'; document.querySelector('.message').style.display='block';">Click Here Cutie</button>
    <svg class="teddy" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
        <!-- Teddy Head -->
        <ellipse cx="100" cy="100" rx="70" ry="60" stroke-width="4" />
        
        <!-- Teddy Ears -->
        <ellipse cx="50" cy="50" rx="30" ry="30" stroke-width="4" />
        <ellipse cx="150" cy="50" rx="30" ry="30" stroke-width="4" />
        
        <!-- Inner Ears -->
        <ellipse cx="50" cy="50" rx="15" ry="15" fill="#f4c6a0" />
        <ellipse cx="150" cy="50" rx="15" ry="15" fill="#f4c6a0" />
        
        <!-- Eyes -->
        <circle cx="80" cy="90" r="10" fill="black" />
        <circle cx="120" cy="90" r="10" fill="black" />
        
        <!-- Nose and Mouth -->
        <ellipse cx="100" cy="110" rx="12" ry="8" fill="black" />
        <path d="M 100 118 Q 90 130 85 120" stroke="black" stroke-width="4" fill="none" />
        <path d="M 100 118 Q 110 130 115 120" stroke="black" stroke-width="4" fill="none" />
        
        <!-- Cheeks -->
        <circle cx="70" cy="110" r="5" fill="#ff9999" />
        <circle cx="130" cy="110" r="5" fill="#ff9999" />
    </svg>
    <div class="message">This is for you, cutie! ❤️</div>
</body>
</html>
