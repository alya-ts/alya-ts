<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Наш Сайт-Подарок</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f7f7f7;
            text-align: center;
            padding: 20px;
        }
        h1 {
            color: #ff6f61;
            font-size: 3em;
        }
        p {
            font-size: 1.2em;
            color: #555;
        }
        .counter {
            font-size: 2em;
            margin: 20px 0;
            color: #333;
        }
        .gallery {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 10px;
        }
        .gallery img {
            width: 200px;
            height: auto;
            border-radius: 10px;
        }
        .music {
            margin-top: 20px;
        }
        iframe {
            border: none;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <h1>Привет, мой любимый!</h1>
    <p>Я хочу сказать тебе, как сильно я скучаю по тебе. Ты делаешь каждый мой день особенным, даже когда мы не рядом.</p>

    <div class="counter">
        Мы вместе уже <span id="days"></span> дней!
    </div>

    <div class="music">
        <p>Вот песня, которая напоминает мне о нас:</p>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/ВОСТАВЬ_СЮДА_ID_ВИДЕО" allow="autoplay; encrypted-media" allowfullscreen></iframe>
    </div>

    <div class="gallery">
        <p>Наши воспоминания:</p>
        <img src="ваша_ссылка_на_фото1.jpg" alt="Фото 1">
        <img src="ваша_ссылка_на_фото2.jpg" alt="Фото 2">
        <img src="ваша_ссылка_на_фото3.jpg" alt="Фото 3">
    </div>

    <script>
        // Установите дату начала ваших отношений
        const startDate = new Date('2023-01-01'); // Измените на нужную вам дату
        const today = new Date();
        const difference = Math.floor((today - startDate) / (1000 * 60 * 60 * 24));

        // Покажем количество дней на сайте
        document.getElementById('days').innerText = difference;
    </script>
</body>
</html
