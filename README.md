<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Oddity Seeker Portfolio</title>
    <style>
        /* Общие стили */
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #1e1e1e;
            color: #ffffff;
            line-height: 1.6;
        }

        h1, h2 {
            color: #f0f0f0;
        }

        a {
            color: #4CAF50;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        /* Контейнер сайта */
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }

        /* Секция "О себе" */
        .about {
            margin-bottom: 40px;
            text-align: center;
        }

        /* Секция "Проекты" */
        .projects {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: space-between;
        }

        .project {
            background-color: #2c2c2c;
            padding: 20px;
            border-radius: 8px;
            flex-basis: 48%;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        .project h3 {
            margin-top: 0;
        }

        .project p {
            margin: 10px 0;
        }

        /* Адаптивность для мобильных устройств */
        @media (max-width: 768px) {
            .project {
                flex-basis: 100%;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- О себе -->
        <section class="about">
            <h1>Oddity Seeker</h1>
            <p>Привет! Я Oddity Seeker, занимаюсь программированием, создаю креативные проекты и контент. На этой странице ты найдёшь мои работы.</p>
        </section>

        <!-- Проекты -->
        <section class="projects">
            <div class="project">
                <h3>Проект 1</h3>
                <p>Описание первого проекта. Этот проект демонстрирует мои навыки в программировании и креативном подходе к решению задач.</p>
                <a href="#">Смотреть проект</a>
            </div>
            <div class="project">
                <h3>Проект 2</h3>
                <p>Описание второго проекта. Здесь я применил свои знания для создания интересного и полезного инструмента.</p>
                <a href="#">Смотреть проект</a>
            </div>
            <!-- Добавь больше проектов по мере необходимости -->
        </section>
    </div>
</body>
</html>
