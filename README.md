[index.html](https://github.com/user-attachments/files/21857854/index.html)
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jana Study – изучайте казахский язык онлайн</title>
    <style>
        :root {
            --primary-color: #365b6d; /* тёмный цвет для фона блоков и бейджей */
            --secondary-color: #6c9286; /* цвет для кнопок */
            --bg-color: #f2f1ec; /* общий фон страницы */
            --text-color: #365b6d; /* основной цвет текста */
        }

        *, *::before, *::after {
            box-sizing: border-box;
        }
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            line-height: 1.5;
        }
        h1, h2, h3 {
            font-weight: 700;
        }

        /* Герой */
        .hero {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: space-between;
            padding: 4rem 2rem;
        }
        .hero .content {
            flex: 1 1 400px;
            max-width: 600px;
            padding-right: 2rem;
        }
        .hero h1 {
            font-size: 3rem;
            margin: 0 0 1rem 0;
        }
        .hero p {
            font-size: 1.2rem;
            margin: 0 0 2rem 0;
        }
        .badges {
            display: flex;
            gap: 1rem;
            flex-wrap: wrap;
            margin-bottom: 2rem;
        }
        .badge {
            background-color: var(--primary-color);
            color: #fff;
            padding: 0.5rem 1rem;
            border-radius: 999px;
            font-size: 0.9rem;
            white-space: nowrap;
        }

        /* Кнопки */
        .btn {
            background-color: var(--secondary-color);
            color: #fff;
            padding: 0.75rem 1.5rem;
            border: none;
            border-radius: 8px;
            font-size: 1rem;
            text-decoration: none;
            display: inline-block;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        .btn:hover {
            background-color: var(--primary-color);
        }
        .hero img {
            flex: 1 1 300px;
            max-width: 450px;
            width: 100%;
            height: auto;
            border-radius: 12px;
        }

        /* Общие секции */
        .section {
            padding: 4rem 2rem;
        }
        .section h2 {
            font-size: 2rem;
            margin-bottom: 1.5rem;
            text-align: center;
        }

        /* Почему с нами */
        .features {
            display: flex;
            flex-wrap: wrap;
            gap: 2rem;
            justify-content: center;
        }
        .feature {
            background-color: var(--primary-color);
            color: #fff;
            padding: 2rem;
            border-radius: 12px;
            flex: 1 1 250px;
            max-width: 300px;
        }
        .feature h3 {
            margin-top: 0;
            margin-bottom: 0.5rem;
            font-size: 1.4rem;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            justify-content: center;
            margin-top: 2rem;
        }
        .gallery img {
            width: 32%;
            border-radius: 12px;
            height: auto;
            object-fit: cover;
        }

        /* Стоимость */
        .pricing {
            display: flex;
            flex-wrap: wrap;
            gap: 2rem;
            justify-content: center;
        }
        .plan {
            background-color: var(--primary-color);
            color: #fff;
            padding: 2rem;
            border-radius: 12px;
            flex: 1 1 250px;
            max-width: 300px;
        }
        .plan h3 {
            margin-top: 0;
            margin-bottom: 1rem;
            font-size: 1.5rem;
        }
        .plan ul {
            list-style: none;
            padding: 0;
            margin: 0 0 1.5rem 0;
        }
        .plan ul li {
            margin: 0.5rem 0;
        }

        /* FAQ */
        .faq {
            max-width: 800px;
            margin: 0 auto;
        }
        .faq details {
            background-color: var(--primary-color);
            color: #fff;
            border-radius: 8px;
            padding: 1rem;
            margin-bottom: 1rem;
        }
        .faq summary {
            font-weight: bold;
            cursor: pointer;
            outline: none;
        }

        /* Подвал */
        footer {
            background-color: var(--primary-color);
            color: #fff;
            padding: 2rem;
            text-align: center;
        }
        footer a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }
        footer a:hover {
            text-decoration: underline;
        }

        /* Адаптивность */
        @media (max-width: 768px) {
            .hero {
                flex-direction: column;
                padding: 2rem 1rem;
            }
            .hero .content {
                padding-right: 0;
                text-align: center;
            }
            .hero img {
                max-width: 100%;
                margin-top: 2rem;
            }
            .features,
            .pricing {
                flex-direction: column;
            }
            .feature,
            .plan {
                max-width: 100%;
            }
            .gallery img {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <header class="hero">
        <div class="content">
            <h1>Добро пожаловать в Jana Study</h1>
            <p>Изучайте казахский язык онлайн с опытными преподавателями. Мы предлагаем индивидуальные занятия, направленные на результат.</p>
            <div class="badges">
                <span class="badge">Бесплатное пробное занятие – 30&nbsp;минут</span>
                <span class="badge">40–50-минутные уроки</span>
            </div>
            <a href="https://wa.me/77089020534?text=Здравствуйте!%20Я%20хочу%20записаться%20на%20казахский%20язык" class="btn">Записаться на занятие</a>
        </div>
        <img src="assets/janna-hero.png" alt="Жанна">
    </header>

    <section class="section">
        <h2>Почему с нами удобно</h2>
        <div class="features">
            <div class="feature">
                <h3>Гибкое расписание</h3>
                <p>Подбираем время занятий под ваш график, чтобы вам было удобно учиться.</p>
            </div>
            <div class="feature">
                <h3>Опытные преподаватели</h3>
                <p>Наши преподаватели имеют большой опыт и помогут вам достичь результата.</p>
            </div>
            <div class="feature">
                <h3>Сильная поддержка</h3>
                <p>Мы всегда готовы помочь и ответить на ваши вопросы во время обучения.</p>
            </div>
            <div class="feature">
                <h3>Персональный менеджер</h3>
                <p>Всегда на связи: быстрый ответ, максимальная поддержка.</p>
            </div>
        </div>
        <div class="gallery">
            <img src="assets/janna-study-2.png" alt="Учим казахский">
            <img src="assets/janna-with-kids.png" alt="Уроки для детей">
            <img src="assets/janna-office.png" alt="Профессиональный преподаватель">
        </div>
    </section>

    <section class="section">
        <h2>Стоимость</h2>
        <div class="pricing">
            <div class="plan">
                <h3>Для детей</h3>
                <ul>
                    <li>8 занятий в месяц — 43&nbsp;000&nbsp;₸</li>
                    <li>12 занятий в месяц — 54&nbsp;000&nbsp;₸</li>
                </ul>
                <a href="https://wa.me/77089020534?text=Здравствуйте!%20Я%20хочу%20узнать%20о%20детском%20тарифе" class="btn">Записаться</a>
            </div>
            <div class="plan">
                <h3>Для взрослых</h3>
                <ul>
                    <li>8 занятий в месяц — 37&nbsp;000&nbsp;₸</li>
                    <li>12 занятий в месяц — 46&nbsp;000&nbsp;₸</li>
                </ul>
                <a href="https://wa.me/77089020534?text=Здравствуйте!%20Я%20хочу%20узнать%20о%20тарифе%20для%20взрослых" class="btn">Записаться</a>
            </div>
        </div>
    </section>

    <section class="section">
        <h2>Часто задаваемые вопросы</h2>
        <div class="faq">
            <details>
                <summary>Как проходит урок?</summary>
                <p>Индивидуальные занятия онлайн. 70% разговорная практика и 30% нужная грамматика. Акцент на разговорном казахском. Результат после первого месяца занятий.</p>
            </details>
            <details>
                <summary>Сколько стоит?</summary>
                <p>Стоимость занятий от 37 000 тенге в месяц.</p>
            </details>
            <details>
                <summary>Как записаться?</summary>
                <p>Свяжитесь с нами через WhatsApp, и мы подберём для вас удобное время для пробного занятия.</p>
            </details>
        </div>
    </section>

    <footer>
        <p>
            <a href="https://wa.me/77089020534">+7&nbsp;708&nbsp;902&nbsp;0534</a> |
            <a href="https://instagram.com/jana_study" target="_blank">@jana_study</a>
        </p>
        <p>© 2025 Jana Study</p>
    </footer>
</body>
</html>
