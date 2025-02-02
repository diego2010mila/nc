# nc
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Para mi niña hermosa</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px;
            transition: background 1s;
        }
        h1 {
            font-size: 50px;
            color: crimson;
        }
        h2 {
            font-size: 30px;
            color: darkblue;
        }
        button {
            font-size: 20px;
            padding: 10px 20px;
            background: pink;
            border: none;
            cursor: pointer;
            margin-top: 20px;
        }
        .hidden {
            display: none;
        }
        .tulip {
            width: 100px;
            position: absolute;
            bottom: 0;
            opacity: 0;
            animation: grow 2s forwards;
        }
        @keyframes grow {
            from {
                opacity: 0;
                transform: translateY(50px) scale(0.5);
            }
            to {
                opacity: 1;
                transform: translateY(0) scale(1);
            }
        }
        #message {
            color: yellow;
            font-size: 24px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <h1>Te amo muchote</h1>
    <h2>Mi niña hermosa, ¿Quisieras ser mi San Valentín?</h2>
    <button onclick="showLove()">CHI (no hay más opciones :3)</button>
    <div id="loveScene" class="hidden">
        <div>
            <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/Tulip_-_floriade_canberra.jpg" class="tulip" style="left: 30%;">
            <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/Tulip_-_floriade_canberra.jpg" class="tulip" style="left: 50%;">
            <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/Tulip_-_floriade_canberra.jpg" class="tulip" style="left: 70%;">
        </div>
        <p id="message">Mi reina, me siento muy agradecido por tenerte en mi vida. Cada día que estoy a tu lado me hace sentir muy feliz y no podría imaginarme estar sin ti, porque tú eres mi vida y mi todo. Recuerda que te amaré hoy, mañana y para toda la eternidad. Te amo demasiado, mi niña bella.</p>
    </div>
    <script>
        function showLove() {
            document.body.style.background = "black";
            document.body.style.color = "white";
            document.getElementById("loveScene").classList.remove("hidden");
        }
    </script>
</body>
</html>
