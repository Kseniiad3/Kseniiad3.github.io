<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Подорожі Чехією</title>
    <style>
        body { 
            margin: 0; 
            font-family: Arial, sans-serif; 
            line-height: 1.6; 
            scroll-behavior: smooth; 
        }
        header {
            background: #2c3e50;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background: #34495e;
            position: sticky;
            top: 0;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            z-index: 1000;
        }
        nav a {
            color: white;
            padding: 12px 15px;
            text-decoration: none;
            display: inline-block;
        }
        nav a:hover {
            background: #1abc9c;
        }
        section {
            padding: 40px;
            max-width: 1000px;
            margin: auto;
        }
        h2 {
            color: #2c3e50;
            border-bottom: 2px solid #1abc9c;
            padding-bottom: 8px;
        }
        .card {
            background: #f4f4f4;
            padding: 15px;
            margin: 10px 0;
            border-radius: 8px;
            border-left: 5px solid #2c3e50;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
            margin-top: 20px;
        }
        .gallery img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }
        .gallery img:hover {
            transform: scale(1.03);
        }
        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 40px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Подорожі Чехією 🇨🇿</h1>
        <p>Інформаційний сайт для туристів та учнів</p>
    </header>

    <nav>
        <a href="#home">Головна</a>
        <a href="#about">Про Чехію</a>
        <a href="#cities">Міста</a>
        <a href="#places">Пам’ятки</a>
        <a href="#transport">Транспорт</a>
        <a href="#tips">Поради</a>
        <a href="#gallery">Галерея</a>
        <a href="#contacts">Контакти</a>
    </nav>

    <section id="home">
        <h2>Головна сторінка</h2>
        <p>Ласкаво просимо на сайт “Подорожі Чехією”. Тут ти знайдеш інформацію про міста, пам’ятки, транспорт і корисні поради для подорожей.</p>
    </section>

    <section id="about">
        <h2>Про Чехію</h2>
        <p>Чехія — країна в центрі Європи, відома своєю історією, замками, архітектурою та культурою.</p>
    </section>

    <section id="cities">
        <h2>Популярні міста</h2>
        <div class="card"><strong>Прага</strong> — столиця Чехії</div>
        <div class="card"><strong>Брно</strong> — студентське місто</div>
        <div class="card"><strong>Карлові Вари</strong> — курортне місто</div>
    </section>

    <section id="places">
        <h2>Визначні пам’ятки</h2>
        <ul>
            <li>Празький град</li>
            <li>Карлів міст</li>
            <li>Староміська площа</li>
        </ul>
    </section>

    <section id="transport">
        <h2>Транспорт і маршрути</h2>
        <p>У Чехії зручний громадський транспорт: метро, трамваї, автобуси та потяги.</p>
    </section>

    <section id="tips">
        <h2>Поради туристам</h2>
        <div class="card">Купуй квитки на транспорт заздалегідь</div>
        <div class="card">Використовуй карти замість готівки</div>
        <div class="card">Вивчай базові фрази чеською</div>
    </section>

    <section id="gallery">
        <h2>Галерея</h2>
        <div class="gallery">
            <img src="https://unsplash.com" alt="Празький град">
            <img src="https://unsplash.com" alt="Карлів міст">
            <img src="https://unsplash.com" alt="Староміська площа">
        </div>
    </section>

    <section id="contacts">
        <h2>Контакти</h2>
        <p><strong>Email:</strong> example@mail.com</p>
        <p><strong>Проєкт:</strong> Учнівський веб-сайт “Подорожі Чехією”</p>
    </section>

    <footer>
        <p>© 2026 Подорожі Чехією | Учнівський проєкт</p>
    </footer>

</body>
</html>
