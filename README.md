<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
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
        }

        .card {
            background: #f4f4f4;
            padding: 15px;
            margin: 10px 0;
            border-radius: 8px;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 10px;
        }

        .gallery img {
            width: 100%;
            border-radius: 10px;
        }

        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 15px;
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
    <div class="card">
        Ласкаво просимо на сайт “Подорожі Чехією”. Тут ти знайдеш інформацію про міста, пам’ятки, транспорт і корисні поради для подорожей.
    </div>
</section>

<section id="about">
    <h2>Про Чехію</h2>
    <div class="card">
        Чехія — країна в центрі Європи, відома своєю історією, замками, архітектурою та культурою.
    </div>
</section>

<section id="cities">
    <h2>Популярні міста</h2>
    <div class="card">Прага — столиця Чехії</div>
    <div class="card">Брно — студентське місто</div>
    <div class="card">Карлові Вари — курортне місто</div>
</section>

<section id="places">
    <h2>Визначні пам’ятки</h2>
    <div class="card">Празький град</div>
    <div class="card">Карлів міст</div>
    <div class="card">Староміська площа</div>
</section>

<section id="transport">
    <h2>Транспорт і маршрути</h2>
    <div class="card">
        У Чехії зручний громадський транспорт: метро, трамваї, автобуси та потяги.
    </div>
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
        <img src="https://upload.wikimedia.org/wikipedia/commons/c/c1/Prague_Castle.jpg">
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/6e/Charles_Bridge_in_Prague.jpg">
        <img src="https://upload.wikimedia.org/wikipedia/commons/3/3e/Brno_City.jpg">
    </div>
</section>

<section id="contacts">
    <h2>Контакти</h2>
    <div class="card">
        Email: example@mail.com <br>
        Проєкт: Учнівський веб-сайт “Подорожі Чехією”
    </div>
</section>

<footer>
    <p>© 2026 Подорожі Чехією | Учнівський проєкт</p>
</footer>

</body>
</html>
