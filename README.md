<!DOCTYPE html>
<html lang="ru">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Запись на мероприятие</title>

    <!-- Подключаем CSS -->
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <div class="event">

        <h1>Frontend Meeting</h1>

        <p>
            Приглашаем всех желающих на интересную встречу,
            посвящённую созданию сайтов и программированию.
        </p>

        <img src="https://images.unsplash.com/photo-1516321318423-f06f85e504b3?auto=format&fit=crop&w=900&q=80"
            alt="Программирование">

        <h2>Что будет на встрече</h2>

        <ul>
            <li>Основы создания сайтов</li>
            <li>Знакомство с HTML и CSS</li>
            <li>Создание небольшой веб-страницы</li>
            <li>Ответы на вопросы участников</li>
        </ul>

        <h2>Записаться на мероприятие</h2>

        <form>
            <label for="name">Имя</label>
            <input type="text" id="name" placeholder="Введите имя">

            <label for="surname">Фамилия</label>
            <input type="text" id="surname" placeholder="Введите фамилию">

            <label for="email">Email</label>
            <input type="email" id="email" placeholder="Введите email">

            <button type="submit">Записаться</button>
        </form>

    </div>

</body>

</html>
body {
    background-color: #eaf2f8;
    color: #222222;
    font-size: 18px;
    padding: 30px;
}

.event {
    background-color: white;
    padding: 30px;
}

h1 {
    color: #1565c0;
    font-size: 36px;
}

h2 {
    color: #1976d2;
    font-size: 26px;
}

img {
    width: 100%;
    max-width: 700px;
}

input {
    display: block;
    padding: 10px;
    margin-bottom: 15px;
}

button {
    padding: 12px;
    background-color: #1976d2;
    color: white;
}
