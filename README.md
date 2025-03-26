
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eslogan Impactante</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: #0a0a0a;
            overflow: hidden;
        }

        /* Estilo para el eslogan */
        .eslogan {
            font-size: 60px;
            font-weight: bold;
            color: #ffffff;
            text-align: center;
            text-transform: uppercase;
            letter-spacing: 4px;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            animation: glowAnimation 1.5s ease-in-out infinite, bounceAnimation 0.7s infinite;
            text-shadow: 0 0 15px #ff0000, 0 0 35px #ff0000, 0 0 55px #ff0000, 0 0 75px #ff0000;
        }

        /* Animación de resplandor (neón) */
        @keyframes glowAnimation {
            0% {
                text-shadow: 0 0 20px #ff6347, 0 0 40px #ff6347, 0 0 60px #ff6347, 0 0 80px #ff6347;
            }
            50% {
                text-shadow: 0 0 20px #32cd32, 0 0 40px #32cd32, 0 0 60px #32cd32, 0 0 80px #32cd32;
            }
            100% {
                text-shadow: 0 0 20px #ff6347, 0 0 40px #ff6347, 0 0 60px #ff6347, 0 0 80px #ff6347;
            }
        }

        /* Animación de rebote para hacer más dinámico el eslogan */
        @keyframes bounceAnimation {
            0% {
                transform: translate(-50%, -50%) scale(1);
            }
            25% {
                transform: translate(-50%, -50%) scale(1.1);
            }
            50% {
                transform: translate(-50%, -50%) scale(1);
            }
            75% {
                transform: translate(-50%, -50%) scale(1.1);
            }
            100% {
                transform: translate(-50%, -50%) scale(1);
            }
        }

        /* Fondo animado */
        @keyframes backgroundAnimation {
            0% {
                background: linear-gradient(45deg, #ff4b5c, #ff6347);
            }
            50% {
                background: linear-gradient(45deg, #32cd32, #00bfff);
            }
            100% {
                background: linear-gradient(45deg, #ff4b5c, #ff6347);
            }
        }

        body {
            animation: backgroundAnimation 6s ease-in-out infinite;
        }
    </style>
</head>
<body>
    <div class="eslogan">
        ¡CON LAS DROGAS, PIERDES MÁS DE LO QUE GANAS!
    </div>
