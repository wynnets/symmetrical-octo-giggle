<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hello!</title>
    <style>
        /* Сброс стандартных отступов */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Красивый живой фон с градиентом */
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background: linear-gradient(-45deg, #ee7752, #e73c7e, #23a6d5, #23d5ab);
            background-size: 400% 400%;
            animation: gradientBG 15s ease infinite;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            overflow: hidden;
        }

        /* Анимация перелива фона */
        @keyframes gradientBG {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        /* Стильный контейнер для текста */
        .card {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
            padding: 40px 70px;
            border-radius: 24px;
            border: 1px solid rgba(255, 255, 255, 0.2);
            box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.2);
            animation: float 4s ease-in-out infinite;
        }

        /* Главная надпись с неоновым эффектом */
        h1 {
            font-size: 4.5rem;
            font-weight: 800;
            color: #ffffff;
            text-transform: uppercase;
            letter-spacing: 4px;
            text-shadow: 0 0 20px rgba(255, 255, 255, 0.5),
                         0 0 40px rgba(255, 255, 255, 0.3);
            text-align: center;
        }

        /* Плавное покачивание карточки вверх-вниз */
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-15px); }
            100% { transform: translateY(0px); }
        }

        /* Адаптация под маленькие экраны мобильных телефонов */
        @media (max-width: 480px) {
            .card {
                padding: 30px 40px;
            }
            h1 {
                font-size: 3rem;
                letter-spacing: 2px;
            }
        }
    </style>
</head>
<body>

    <div class="card">
        <h1>Hello</h1>
    </div>

</body>
</html>
