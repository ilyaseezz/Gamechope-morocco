<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>GameShop Morocco | شحن الألعاب</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, sans-serif;
      background: #08080d;
      color: white;
    }

    header {
      background: linear-gradient(135deg, #15152a, #08080d);
      padding: 45px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 38px;
      margin-bottom: 10px;
    }

    header p {
      color: #aaa;
      font-size: 17px;
    }

    nav {
      background: #11111a;
      padding: 15px;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 10;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 12px;
      font-weight: bold;
    }

    nav a:hover {
      color: #00ff88;
    }

    .container {
      max-width: 1000px;
      margin: auto;
      padding: 30px 18px;
    }

    .title {
      text-align: center;
      margin-bottom: 25px;
      font-size: 28px;
    }

    .games {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 18px;
    }

    .card {
      background: #15151f;
      border: 1px solid #292936;
      border-radius: 18px;
      padding: 25px;
      text-align: center;
      transition: 0.25s;
    }

    .card:hover {
      transform: translateY(-5px);
      border-color: #00ff88;
    }

    .icon {
      font-size: 50px;
      margin-bottom: 12px;
    }

    .card h3 {
      font-size: 23px;
      margin-bottom: 10px;
    }

    .card p {
      color: #aaa;
      line-height: 1.6;
    }

    .btn {
      display: inline-block;
      margin-top: 18px;
      padding: 12px 20px;
      background: #00c968;
      color: white;
      text-decoration: none;
      border-radius: 12px;
      font-weight: bold;
    }

    .btn:hover {
      background: #00e879;
    }

    .contact {
      margin-top: 35px;
      background: #12121b;
      border-radius: 18px;
      padding: 30px;
      text-align: center;
    }

    .phone {
      font-size: 25px;
      margin: 12px 0;
      direction: ltr;
    }

    footer {
      text-align: center;
      padding: 30px;
      color: #777;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 30px;
      }

      nav a {
        margin: 0 5px;
        font-size: 14px;
      }
    }
  </style>
</head>

<body>

<header>
  <h1>🎮 GameShop Morocco</h1>
  <p>شحن الألعاب وبيع الحسابات</p>
</header>

<nav>
  <a href="#games">الألعاب</a>
  <a href="#accounts">الحسابات</a>
  <a href="#contact">تواصل معنا</a>
</nav>

<section class="container" id="games">

  <h2 class="title">🎮 خدمات الألعاب</h2>

  <div class="games">

    <div class="card">
      <div class="icon">🔥</div>
      <h3>Free Fire</h3>
      <p>
        شحن الجواهر وخدمات Free Fire.
      </p>

      <a
        class="btn"
        href="https://wa.me/212637067853?text=سلام،%20بغيت%20شحن%20Free%20Fire"
        target="_blank">
        اطلب الآن
      </a>
    </div>


    <div class="card">
      <div class="icon">⚽</div>
      <h3>PES</h3>
      <p>
        خدمات وشحن وطلبات PES.
      </p>

      <a
        class="btn"
        href="https://wa.me/212637067853?text=سلام،%20بغيت%20خدمة%20PES"
        target="_blank">
        اطلب الآن
      </a>
    </div>


    <div class="card">
      <div class="icon">🧱</div>
      <h3>Roblox</h3>
      <p>
        شحن وطلبات Roblox.
      </p>

      <a
        class="btn"
        href="https://wa.me/212637067853?text=سلام،%20بغيت%20شحن%20Roblox"
        target="_blank">
        اطلب الآن
      </a>
    </div>

  </div>
</section>


<section class="container" id="accounts">

  <h2 class="title">👤 بيع الحسابات</h2>

  <div class="card">

    <div class="icon">🎮</div>

    <h3>حسابات الألعاب</h3>

    <p>
      حسابات ألعاب حسب المتوفر.
      تواصل معنا لمعرفة الحسابات والأسعار المتوفرة.
    </p>

    <a
      class="btn"
      href="https://wa.me/212637067853?text=سلام،%20بغيت%20نشوف%20الحسابات%20المتوفرة"
      target="_blank">
      شوف الحسابات
    </a>

  </div>

</section>


<section class="container" id="contact">

  <div class="contact">

    <h2>📱 تواصل معنا</h2>

    <p class="phone">0637067853</p>

    <a
      class="btn"
      href="https://wa.me/212637067853"
      target="_blank">
      💬 واتساب
    </a>

  </div>

</section>


<footer>
  © 2026 GameShop Morocco
</footer>

</body>
</html>
