<!DOCTYPE html>
<html lang="uk">
<head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">       
        <title>Книжковий Рай</title>
        <link rel="stylesheet" href="style.css">
</head>
<body>
        <main class="section-main">
<img class="section-main-logo" src"https://i.pinimg.com/474x/82/af/4b/82af4bb76f88b45995b8bb3b08187b98.jpg" alt="логотип">
        <h1 class="section-main-title">Книжковий рай</h1>
        <h2 class="section-main-subtitle">Відкрий для себе наступну чудову книгу</h2>
        <button class="section-main-button" type="button">
        </main>

        <section class="second-section">
     <img src="https://img.pikbest.com/png-images/20241016/creative-book-logo-vector-design_10968791.png!bw700" alt="зображення бібліотеки"
     class="second-section-img">
      <div class="second-section-info">
     </div>
<div class="info-block">
    <h3 class="section-subtitle">Про нашу бібліотеку</h3>
    <p>
        Ласкаво просимо до нашої бібліотеки, де ви знайдете широкий вибір книг для будь-якого віку та вподобань.
        Приходьте та насолоджуйтеся читанням у затишній атмосфері!
    </p>

<p class="second-section-name"><span class="second-section-name2">
ГАПАНЧАК МАРГАРИТА, КОБЖИЦЬКА САБІНА, ШЕВЧУК ІЛОНА</span> - засновники Книжкового Раю</p>
        </section>

        <section class="third-section">
     <h3 class="section-subtitle">РЕКОМЕНДОВАНІ КНИГИ</h3>
             <h3 class="section-title">Наша колекція</h3>
<div class="third-section-books">

<div class="third-section-book">
                <img src="https://nashformat.ua/files/products/nespodivane-kino.800x800.jpg" alt="Книга 1" class="book-img">
                <h4 class="book-title">Несподіване кіно</h4>
                <p class="book-author">Наталія Ясіновська</p>
                <p class="book-price">160 грн</p>
            </div>

<div class="third-section-book">
                <img src="https://upload.wikimedia.org/wikipedia/uk/6/6c/HPandPhStone_Ukr.jpg" alt="Книга 2" class="book-img">
                <h4 class="book-title">Гаррі Поттер і філософський камінь</h4>
                <p class="book-author">Дж. К. Ролінґ</p>
                <p class="book-price">450 грн</p>
            </div>

<div class="third-section-book">
                <img src="https://bookopt.com.ua/media/catalog/product/cache/image/850x/c/h/chasovij-kljuch-chasodii_4.webp" alt="Книга 3" class="book-img">
                <h4 class="book-title">Часодії. Часовий ключ</h4>
                <p class="book-author">Наталія Щерба</p>
                <p class="book-price">650 грн</p>
            </div>

<div class="third-section-book">
                <img src="https://book-ye.com.ua/media/catalog/product/cache/79524a38d3bc3d0f3b6015a08841400c/4/f/4f10140d-69ff-11ea-812b-000c29ae1566_76d94558-6a00-11ea-812b-000c29ae1566.jpg" alt="Книга 4" class="book-img">
                <h4 class="book-title">Буба</h4>
                <p class="book-author">Барбара Космовська</p>
                <p class="book-price">260 грн</p>
            </div>
</div>
        </section>

        <footer class="footer">
<h3 class="section-title footer-title">КНИЖКОВИЙ РАЙ</h3>
<h3 class="section-title footer-title">Приєднуйтесь до нашої спільноти</h3>
        <p class="footer-text"><span class="footer-text-main">Підпишіться на нашу розсилку, щоб отримувати останні новини по новинки, ексклюзивні пропозиції та багато чого іншого.</span><br> Для запитів, будь ласка, зв'яжіться з нами.</p>

<form action="" class="footer-form">
            <p class="form-title">Ім'я</p>
            <input type="text" id="name" class="form-input">
            <p class="form-title">Електронна пошта</p>
            <input type="email" id="email" class="form-input">
            <p class="form-title">Телефон</p>
            <input type="tel" id="phone" class="form-input">
            <button class="footer-button">Підписатися</butto>
        </form>
        </footer>

                    
</body>
</html>
body {
  margin: 0;
  padding: 0;
  font-family: 'Roboto', sans-serif;
  color: #333;
  background-color: #eaeaea;
  font-size: 16px;
}

.section-main {
  background-color: #556b2f;
  padding-top: 40px;
  padding-bottom: 120px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.section-main-title {
    margin-top: 40px;
    margin-bottom: 20px;
    color: #fff;
    font-family: 'Lora', serif;
    font-size: 55px;
    font-weight: 700;
}

.section-main-subtitle {
  margin-bottom: 40px;
  color: #fff;
  font-size: 22px;
}

.section-main-button {
  background-color: #8fbc8f;
  border: none; 
  border-radius: 25px;
  color: #fff;
  font-weight: 700;
  text-transform: uppercase;
  padding: 12px 30px;
  cursor: pointer;
}

.second-section {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 100px 0;
}

.footer-title {
  color: #fff;
}

.section-main img {
    width: 160px;
}

.second-section img {
    width: 500px;
    border: 5px solid #556b2f;
    border-radius: 20px;
}

.second-section-info {
    margin-left: 30px;
    max-width: 600px;
}

.section-subtitle {
    margin-top: 0;
    margin-bottom: 10px;
    color: #8fbc8f;
    font-size: 18px;
    font-weight: 700;
    text-transform: uppercase;
}

.section-title {
    margin-top: 0;
    margin-bottom: 40px;
    color: #556b2f;
    font-size: 32px;
    font-weight: 700;
    text-transform: capitalize;
}

.second-section-text {
    margin: 30px;
    color: #666;
    font-size: 18px;
}

.second-section-name {
    color: #556b2f;
    text-transform: capitalize;
}

.second-section-name2 {
    color: #8fbc8f;
    font-weight: 700;
    text-transform: uppercase;
}

.third-section {
    display: flex;
    flex-direction: column;
    align-items: center;
    background-color: #f5f5f5;
    padding: 100px 0;
}

.third-section-books {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 50px;
    flex-wrap: wrap;
}

.third-section-book {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 10px 20px;
}

.book-img {
    height: 200px;
}

.book-title {
    margin: 10px 0 5px 0;
    color: #556b2f;
    font-size: 22px;
    font-weight: 700;
}

.book-author {
    margin: 2px 0;
    color: #666;
}

.book-price {
    margin: 0;
    color: #8fbc8f;
    font-size: 20px;
    font weight: 700;
}

.footer {
    display: flex;
    flex-direction: column;
    align-items: center;
    background-color: #2f4f4f;
    padding: 100px 0;
}

.footer-text {
    width: 600px;
    text-align: center;
    margin-top: 0;
    margin-bottom: 20px;
    color: #8fbc8f;
    font-size: 20px;
}

.footer-text-main {
    color: #fff;
}

.footer-form {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.form-title {
    margin-top: 20px;
    margin-bottom: 10px;
    text-align: center;
    color: #fff;
    font-weight: 700;
    text-transform: uppercase;
}

.form-input {
    width: 400px;
    height: 40px;
    margin-bottom: 10px;
    padding: 0 10px:
    background-color: #2f4f4f;
    color: #fff;
    border: 1px solid #fff;
    border-radius: 8px;
}

.footer-button {
    margin-top: 30px;
    padding: 10px 20px;
    background-color: #8fbc8f;
    color: #fff;
    font-weight: 700;
    border: none;
    border-radius: 25px;
    cursor: pointer;
}
