<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>衣服配色網站</title>
  <link rel="stylesheet" href="pink.css">
</head>
<body>
<header>
  <h1>衣服配色網站</h1>
</header>

<nav>
  <ul>
    <li><a href="#home">首頁</a></li>
    <li><a href="#about">抽抽幸運色!</a></li>
    <li><a href="#services">服務</a></li>
    <li><a href="#contact">聯絡我們</a></li>
  </ul>
</nav>

<main>
  <section id="home">
    <h2>Sorry......時間不夠了!</h2>

  </section>

  <section id="about">
    <h2>抽抽幸運色!</h2>
    <p>點選方塊，看看自己今天的幸運色試試是什麼吧!</p>
    <div class="color-boxes">
      <div class="color-box"></div>
      <div class="color-box"></div>
      <div class="color-box"></div>
      <div class="color-box"></div>
    </div>
  </section>

  <section id="services">
    <h2>我們的服務</h2>
    <p>我們提供各種服飾，按下訂閱，補貨時能快速通知您。</p>
    <!-- 訂閱按鈕 -->
    <button id="subscribe-btn">訂閱</button>
  </section>

  <section id="contact">
    <h2>聯絡我們</h2>
    <p>想要聯絡我們嗎？隨時發送郵件給我們，我們會很快回覆你！</p>
    <!-- 留言板 -->
    <form id="contact-form">
      <textarea id="message" placeholder="請輸入您的留言"></textarea>
      <br />
      <button type="submit">提交</button>
    </form>
  </section>
</main>

<footer>
  <p>版權所有 &copy; 2024 Weekend</p>
</footer>

<!-- 浮動視窗 -->
<div id="luck-modal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    <p>我們已收到您的來信，請稍等片刻，我們會盡快提供服務！</p>
  </div>
</div>

<script src="script1.js"></script>
</body>
</html>

const path = require('path');

app.get('/', (req, res) => {
res.sendFile(path.join(__dirname, 'page.html'));
});
