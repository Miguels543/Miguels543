<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Miguel Suarez - Especialista en Desarrollo Tecnológico</title>
    <style>
        body {
            background-color: #00101a;
            color: #ffffff;
            font-family: 'Arial', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            text-align: center;
            position: relative;
        }
        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
            position: relative;
            padding: 20px;
        }
        .title {
            color: #00ff00;
            font-size: 2em;
        }
        .text-container {
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
            z-index: 1;
            padding: 20px;
        }
        .text-container::before {
            content: '';
            position: absolute;
            top: 50%;
            left: 50%;
            width: 200%;
            height: 200%;
            background-image: 
                linear-gradient(90deg, rgba(0, 255, 0, 0.3) 1px, transparent 1px),
                linear-gradient(0deg, rgba(0, 255, 0, 0.3) 1px, transparent 1px),
                linear-gradient(45deg, rgba(0, 255, 0, 0.3) 1px, transparent 1px),
                linear-gradient(-45deg, rgba(0, 255, 0, 0.3) 1px, transparent 1px);
            background-size: 20px 20px;
            transform: translate(-50%, -50%);
            z-index: -1;
            border-radius: 50%;
            opacity: 0.5;
        }
        .text {
            font-size: 1.2em;
            margin: 0 20px;
        }
        .icon {
            font-size: 50px;
            color: #ff9100;
            margin-right: 10px;
        }
        .laptop {
            font-size: 50px;
            color: #00ff00;
            margin-left: 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="title">Miguel Suarez</div>
        <div class="text-container">
            <div class="icon">💡</div>
            <div class="text">
                Especialista en desarrollo tecnológico y sistemas<br>
                Ayudando a startups a optimizar su presencia digital con<br>
                soluciones full-stack, aplicaciones móviles y ciberseguridad.
            </div>
            <div class="laptop">💻</div>
        </div>
    </div>
</body>
</html>

