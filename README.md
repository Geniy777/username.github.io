# username.github.io
<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Книжний Рай</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f8f4e3;
            color: #333;
        }

        header {
            background: #8b5e34;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background: #d4a373;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .hero {
            padding: 60px 20px;
            text-align: center;
            background: #faedcd;
        }

        .books {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
            gap: 20px;
        }

        .book {
            background: white;
            padding: 15px;
            width: 250px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            text-align: center;
        }

        .book img {
            width: 100%;
            border-radius: 10px;
        }

        footer {
            background: #8b5e34;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <h1>Книжний Рай</h1>
    <p>Місце, де кожен знайде свою історію</p>
</header>

<nav>
    <a href="#">Головна</a>
    <a href="#">Каталог</a>
    <a href="#">Новинки</a>
    <a href="#">Контакти</a>
</nav>

<section class="hero">
    <h2>Ласкаво просимо до світу книжок!</h2>
    <p>Обирай, читай, надихайся ♥</p>
</section>

<section class="books">
    <div class="book">
        <img src="https://via.placeholder.com/250x350" alt="Книга 1">
        <h3>Назва книги 1</h3>
        <p>Короткий опис книги.</p>
    </div>

    <div class="book">
        <img src="https://via.placeholder.com/250x350" alt="Книга 2">
        <h3>Назва книги 2</h3>
        <p>Короткий опис книги.</p>
    </div>

    <div class="book">
        <img src="https://via.placeholder.com/250x350" alt="Книга 3">
        <h3>Назва книги 3</h3>
        <p>Короткий опис книги.</p>
    </div>
</section>

<footer>
    <p>© 2025 Книжний Рай. Усі права захищено.</p>
</footer>

</body>
</html>
