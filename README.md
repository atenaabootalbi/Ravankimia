# Ravankimia
<!DOCTYPE html>
<html lang="fa">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>روان کیمیا</title>
  <style>
    body {
      margin: 0;
      font-family: 'Vazirmatn', sans-serif;
      background: linear-gradient(to bottom, #fdf6e3, #dbeaf5);
      color: #333;
    }
    header {
      background-color: #fff3e0;
      padding: 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .logo {
      display: flex;
      align-items: center;
      gap: 10px;
    }
    .logo img {
      height: 40px;
    }
    .logo h1 {
      font-size: 24px;
      color: #7b4f20;
    }
    nav a {
      margin-left: 20px;
      text-decoration: none;
      color: #5d4037;
      font-weight: bold;
    }
    .hero {
      background: url('https://cdn.midjourney.com/e65f9e91-e655-4fd1-86e4-ea0dbdd61203/0_0.png') no-repeat center center;
      background-size: cover;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      color: #fff;
      position: relative;
    }
    .hero::after {
      content: '';
      position: absolute;
      top: 0;
      right: 0;
      bottom: 0;
      left: 0;
      background: rgba(0,0,0,0.4);
    }
    .hero h2 {
      position: relative;
      font-size: 36px;
      z-index: 1;
    }
    .hero button {
      margin-top: 20px;
      padding: 12px 24px;
      font-size: 18px;
      background-color: #ffb74d;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      position: relative;
      z-index: 1;
    }
    footer {
      background-color: #eee;
      padding: 20px;
      text-align: center;
      font-size: 14px;
      color: #666;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fd/Butterfly_icon.svg/1024px-Butterfly_icon.svg.png" alt="لوگو پروانه">
      <h1>روان کیمیا</h1>
    </div>
    <nav>
      <a href="#articles">مقالات</a>
      <a href="#packages">پکیج‌ها</a>
      <a href="#contact">تماس با ما</a>
    </nav>
  </header>

  <section class="hero">
    <h2>به دنیای درونی و کیمیاگری روان خوش آمدید</h2>
    <button onclick="window.scrollTo({ top: document.body.scrollHeight, behavior: 'smooth' });">ورود به سایت</button>
  </section>

  <footer>
    طراحی شده با الهام از نمادهای یونگ، گل نیلوفر، یوگا و پروانه.
  </footer>
</body>
</html>
