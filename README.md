<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sen Sulu – Магазин косметики</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background: linear-gradient(135deg, #fce4ec, #f8bbd0, #f48fb1);
      background-attachment: fixed;
      color: #333;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: rgba(255, 255, 255, 0.9);
      padding: 15px 30px;
      position: sticky;
      top: 0;
      z-index: 1000;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }

    .logo {
      font-size: 28px;
      font-weight: bold;
      color: #e91e63;
      text-shadow: 1px 1px 4px rgba(0,0,0,0.2);
    }

    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }

    nav a:hover {
      color: #e91e63;
    }

    .container {
      max-width: 1200px;
      margin: auto;
      padding: 20px;
    }

    h1 {
      text-align: center;
      margin-bottom: 30px;
      font-size: 36px;
      color: #d81b60;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
    }

    .product {
      background: #fff;
      border-radius: 15px;
      padding: 15px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
      text-align: center;
      transition: transform 0.3s;
    }

    .product:hover {
      transform: translateY(-5px);
    }

    .product img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 10px;
    }

    .product h3 {
      margin: 15px 0 10px;
      font-size: 18px;
      color: #444;
    }

    .price {
      font-size: 16px;
      color: #d81b60;
      font-weight: bold;
    }

    button {
      margin-top: 10px;
      padding: 10px 20px;
      background: #e91e63;
      color: #fff;
      border: none;
      border-radius: 20px;
      cursor: pointer;
      transition: background 0.3s;
    }

    button:hover {
      background: #ad1457;
    }

    .cart {
      margin-top: 40px;
      padding: 20px;
      background: rgba(255,255,255,0.95);
      border-radius: 15px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
    }

    .cart h2 {
      margin-top: 0;
    }

    .cart ul {
      list-style: none;
      padding: 0;
    }

    .cart li {
      margin: 5px 0;
      padding: 5px;
      border-bottom: 1px solid #eee;
    }

    footer {
      margin-top: 40px;
      padding: 20px;
      text-align: center;
      background: rgba(255,255,255,0.8);
      font-size: 14px;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">Sen Sulu</div>
    <nav>
      <a href="#">Главная</a>
      <a href="#">Товары</a>
      <a href="#">Контакты</a>
    </nav>
  </header>

  <div class="container">
    <h1>Каталог косметики</h1>
    <div class="products">
      <div class="product">
        <img src="https://share.google/images/FEdxqLitoKeohV14h" alt="Крем">
        <h3>Увлажняющий крем</h3>
        <p class="price">2500 ₸</p>
        <button onclick="addToCart('Увлажняющий крем', 2500)">В корзину</button>
      </div>
      <div class="product">
        <img src="<img width="3840" height="2122" alt="ZqVuY8eN-cover-h" src="https://github.com/user-attachments/assets/694cea38-b033-429a-8b57-27df8d2c58e5" />
        " alt="Помада">
        <h3>Губная помада</h3>
        <p class="price">1800 ₸</p>
        <button onclick="addToCart('Губная помада', 1800)">В корзину</button>
      </div>
      <div class="product">
        <img src="![7247378782](https://github.com/user-attachments/assets/10f36daa-8d6d-4bdd-b415-57bcce331e9d)
          " alt="Тушь">
        <h3>Тушь для ресниц</h3>
        <p class="price">2200 ₸</p>
        <button onclick="addToCart('Тушь для ресниц', 2200)">В корзину</button>
      </div>
      <div class="product">
        <img src="![cubs6ilj9qme4hnpc75g](https://github.com/user-attachments/assets/23f59328-d382-4725-8ad1-8612d75486ac)
          " alt="Тональный крем">
        <h3>Тональный крем</h3>
        <p class="price">3000 ₸</p>
        <button onclick="addToCart('Тональный крем', 3000)">В корзину</button>
      </div>
      <div class="product">
        <img src="<img width="900" height="623" alt="Day_Dreams_Ð¡Ð¶Ð°ÑÑÐµ" src="https://github.com/user-attachments/assets/a87ec696-ceeb-4cf0-9d2e-b4f895b12b8a" />
" alt="Парфюм">
        <h3>Парфюм</h3>
        <p class="price">7500 ₸</p>
        <button onclick="addToCart('Парфюм', 7500)">В корзину</button>
      </div>
      <div class="product">
        <img src="![1](https://github.com/user-attachments/assets/153e53f9-f939-4852-8b61-fa807c299ef9)
" alt="Сыворотка">
        <h3>Сыворотка для лица</h3>
        <p class="price">4200 ₸</p>
        <button onclick="addToCart('Сыворотка для лица', 4200)">В корзину</button>
      </div>
      <div class="product">
        <img src="![1-2](https://github.com/user-attachments/assets/2ba66631-3354-427b-ada6-2697a674e189)
" alt="Пудра">
        <h3>Пудра</h3>
        <p class="price">2100 ₸</p>
        <button onclick="addToCart('Пудра', 2100)">В корзину</button>
      </div>
      <div class="product">
        <img src="![Kachel_Nail-Polish-Trends](https://github.com/user-attachments/assets/20ced9a7-1900-44c6-b4c6-93ca88b29ed4)
" alt="Лак для ногтей">
        <h3>Лак для ногтей</h3>
        <p class="price">900 ₸</p>
        <button onclick="addToCart('Лак для ногтей', 900)">В корзину</button>
      </div>
      <div class="product">
        <img src="![post](https://github.com/user-attachments/assets/7ef2269a-5387-4ec2-a8ac-bcb0a4123c93)
" alt="Карандаш для глаз">
        <h3>Карандаш для глаз</h3>
        <p class="price">1500 ₸</p>
        <button onclick="addToCart('Карандаш для глаз', 1500)">В корзину</button>
      </div>
      <div class="product">
        <img src="![post-Blesk-Balzam-novyj-1](https://github.com/user-attachments/assets/4b9edb77-ca0e-4e6b-a778-c5f0eae34ee5)
" alt="Бальзам для губ">
        <h3>Бальзам для губ</h3>
        <p class="price">1200 ₸</p>
        <button onclick="addToCart('Бальзам для губ', 1200)">В корзину</button>
      </div>
    </div>

    <div class="cart">
      <h2>Корзина</h2>
      <ul id="cart-items"></ul>
      <p><strong>Итого: <span id="total">0</span> ₸</strong></p>
    </div>
  </div>

  <footer>
    © 2025 Sen Sulu – Онлайн-магазин косметики
  </footer>

  <script>
    let cart = [];
    let total = 0;

    function addToCart(product, price) {
      cart.push({product, price});
      total += price;
      renderCart();
    }

    function renderCart() {
      const cartList = document.getElementById('cart-items');
      cartList.innerHTML = '';
      cart.forEach(item => {
        const li = document.createElement('li');
        li.textContent = `${item.product} – ${item.price} ₸`;
        cartList.appendChild(li);
      });
      document.getElementById('total').textContent = total;
    }
  </script>
</body>
</html># projectHTML....
