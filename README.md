
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мой Первый Сайт</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
        }
        header {
            background: #35424a;
            color: #ffffff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            color: #35424a;
            text-decoration: none;
        }
        main {
            background: #ffffff;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            margin-top: 20px;
            color: #777;
        }
    </style>
</head>
<body>

<header>
    <h1>Добро пожаловать на мой сайт!</h1>
</header>

<nav>
    <a href="#about">О сайте</a>
    <a href="#services">Услуги</a>
    <a href="#contact">Контакты</a>
</nav>

<main>
    <section id="about">
        <h2>О сайте</h2>
        <p>Это мой первый сайт, созданный с использованием HTML и CSS. Здесь вы можете узнать больше обо мне и моих услугах.</p>
        <img src="https://via.placeholder.com/400" alt="Пример изображения" />
    </section>

    <section id="services">
        <h2>Услуги</h2>
        <ul>
            <li>Веб-разработка</li>
            <li>Дизайн сайтов</li>
            <li>SEO-оптимизация</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Контакты</h2>
        <p>Вы можете связаться со мной по электронной почте: 
           <a href="mailto:example@example.com">example@example.com</a></p>
    </section>
</main>

<footer>
    <p>&copy; 2024 Мой Первый Сайт</p>
</footer>

</body>
</html>
