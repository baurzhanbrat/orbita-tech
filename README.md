# orbita-tech
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ORBITA-TECH 🚀 — Электроника Космической Точности</title>
    <link rel="stylesheet" href="style.css"> <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>

    <header class="header">
        <div class="container">
            <h1>ORBITA-TECH 🚀</h1>
            <p>Технологии, которые выводят за пределы. Электроника космической точности.</p>
            <nav>
                <a href="#featured">Звёздные Предложения</a>
                <a href="#mobile">Мобильные Устройства</a>
                <a href="#pc">Компьютеры</a>
                <a href="#">Контакты</a>
            </nav>
        </div>
    </header>

    <main class="container">

        <section id="featured" class="section-block dark-blue-bg">
            <h2>🌠 ЗВЁЗДНЫЕ ПРЕДЛОЖЕНИЯ</h2>
            <div class="product-grid">

                <div class="product-card">
                    <h3>Ноутбук "Плутон-M"</h3>
                    <p>Core i7, 16GB RAM, 1TB SSD, 15.6" 4K OLED</p>
                    <span class="price">599 990 ₸</span>
                    <button class="btn-buy">Купить</button>
                </div>

                <div class="product-card">
                    <h3>Смартфон "Созвездие S12"</h3>
                    <p>256GB, 108MP Камера, Батарея 5000 mAh</p>
                    <span class="price">385 000 ₸</span>
                    <button class="btn-buy">Купить</button>
                </div>

                <div class="product-card">
                    <h3>Наушники "Метеорит"</h3>
                    <p>Шумоподавление, 40 часов работы, Аквамарин</p>
                    <span class="price">55 500 ₸</span>
                    <button class="btn-buy">Купить</button>
                </div>
            </div>
        </section>
        
        <section id="mobile" class="section-block">
            <h2>📱 Категория: Мобильные Устройства</h2>
            <div class="product-grid">
                <div class="product-card">
                    <h3>Смартфон "Небула X"</h3>
                    <p class="description">Безграничный экран, производительность на уровне космического корабля.</p>
                    <span class="price">295 000 ₸</span>
                    <button class="btn-cart">В Корзину</button>
                </div>
                <div class="product-card">
                    <h3>Планшет "Спутник P9"</h3>
                    <p class="description">Лёгкий и мощный, идеален для межгалактических путешествий.</p>
                    <span class="price">189 990 ₸</span>
                    <button class="btn-cart">В Корзину</button>
                </div>
            </div>
        </section>

        <section id="pc" class="section-block dark-blue-bg">
            <h2>🖥️ Категория: Компьютеры и Периферия</h2>
            <div class="product-grid">
                <div class="product-card">
                    <h3>Монитор "Горизонт 34"</h3>
                    <p class="description">Изогнутый 34-дюймовый дисплей, 144 Гц, погружение в другие миры.</p>
                    <span class="price">240 000 ₸</span>
                    <button class="btn-cart">В Корзину</button>
                </div>
                <div class="product-card">
                    <h3>Клавиатура "Астероид"</h3>
                    <p class="description">Тактильные переключатели, настраиваемая RGB-подсветка.</p>
                    <span class="price">35 990 ₸</span>
                    <button class="btn-cart">В Корзину</button>
                </div>
            </div>
        </section>

    </main>

    <footer>
        <p>© 2024 ORBITA-TECH. Мы доставляем технологии в любую точку Галактики (и Казахстана).</p>
    </footer>

</body>
</html>
/* Основные переменные для цветов */
:root {
    --color-black: #000000;
    --color-dark-blue: #000033; /* Тёмно-синий для блоков */
    --color-text: #ffffff; /* Белый/Светлый текст */
    --color-accent: #00FFFF; /* Яркий аквамарин/Голубой для акцентов */
    --color-light-blue: #2A48C0; /* Светлее синий для некоторых фонов */
}

/* Общий сброс и настройки */
body {
    font-family: 'Orbitron', sans-serif; /* Космический шрифт */
    background-color: var(--color-black); /* Главный фон - ЧЁРНЫЙ */
    color: var(--color-text);
    margin: 0;
    padding: 0;
    line-height: 1.6;
}

.container {
    width: 90%;
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px 0;
}

/* === ШАПКА / ЗАГОЛОВОК === */
.header {
    background-color: var(--color-dark-blue);
    padding: 40px 0;
    text-align: center;
    border-bottom: 3px solid var(--color-accent);
}

.header h1 {
    font-size: 3em;
    color: var(--color-accent); /* Яркий цвет для названия */
    margin-bottom: 5px;
}

.header p {
    font-size: 1.2em;
    font-style: italic;
    margin-bottom: 20px;
}

.header nav a {
    color: var(--color-text);
    text-decoration: none;
    margin: 0 15px;
    font-weight: bold;
    padding: 5px 10px;
    transition: color 0.3s, border-bottom 0.3s;
}

.header nav a:hover {
    color: var(--color-accent);
    border-bottom: 2px solid var(--color-accent);
}

/* === СЕКЦИИ ТОВАРОВ === */
.section-block {
    padding: 60px 0;
    text-align: center;
}

.dark-blue-bg {
    background-color: var(--color-dark-blue);
}

.section-block h2 {
    font-size: 2.5em;
    margin-bottom: 40px;
    color: var(--color-accent);
}

.product-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 30px;
    justify-content: center;
}

.product-card {
    background-color: var(--color-light-blue); /* Чуть светлее синий для карточек */
    border: 1px solid var(--color-accent);
    padding: 20px;
    border-radius: 10px;
    width: 300px;
    box-shadow: 0 0 20px rgba(0, 255, 255, 0.2); /* Свечение */
    transition: transform 0.3s, box-shadow 0.3s;
    text-align: left;
}

.product-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 0 30px rgba(0, 255, 255, 0.5);
}

.product-card h3 {
    color: var(--color-text);
    margin-top: 0;
    font-size: 1.5em;
}

.product-card p {
    color: #cccccc;
    min-height: 40px; /* Чтобы карточки были одинаковыми по высоте */
}

.price {
    display: block;
    font-size: 1.8em;
    color: var(--color-accent);
    font-weight: bold;
    margin: 15px 0;
}

/* === КНОПКИ === */
.btn-buy, .btn-cart {
    background-color: var(--color-accent);
    color: var(--color-black);
    border: none;
    padding: 10px 20px;
    font-size: 1.1em;
    font-weight: bold;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s, transform 0.1s;
}

.btn-buy:hover, .btn-cart:hover {
    background-color: #33ffff;
    transform: scale(1.05);
}

/* === ПОДВАЛ === */
footer {
    background-color: var(--color-black);
    color: #aaa;
    text-align: center;
    padding: 20px 0;
    border-top: 1px solid var(--color-dark-blue);
    font-size: 0.9em;
}
