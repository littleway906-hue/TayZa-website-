<!DOCTYPE html>
<html lang="my">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>TayZa စားသောက်ဆိုင်</title>
  <style>
    body {
      font-family: "Myanmar Text", sans-serif;
      margin: 0;
      background-color: #fff8f0;
      color: #4a342e;
    }
    header {
      background-color: #d2691e;
      color: white;
      padding: 20px 0;
      text-align: center;
      font-size: 2.5rem;
      font-weight: bold;
      letter-spacing: 3px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
    }
    nav {
      background-color: #c1501a;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 12px 0;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: 600;
      font-size: 1.2rem;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #ffe4c4;
    }
    main {
      max-width: 900px;
      margin: 30px auto;
      padding: 0 20px;
    }
    h2 {
      border-bottom: 2px solid #d2691e;
      padding-bottom: 8px;
      margin-bottom: 20px;
    }
    .menu-item {
      display: flex;
      align-items: center;
      background-color: #fff3e6;
      border-radius: 8px;
      margin-bottom: 20px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      padding: 12px;
    }
    .menu-item img {
      width: 120px;
      height: 90px;
      border-radius: 8px;
      object-fit: cover;
      margin-right: 20px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.15);
    }
    .menu-info {
      flex-grow: 1;
    }
    .menu-info h3 {
      margin: 0 0 8px 0;
      font-size: 1.4rem;
      color: #a64c15;
    }
    .menu-info p {
      margin: 0 0 8px 0;
      line-height: 1.3;
    }
    .menu-price {
      font-weight: bold;
      font-size: 1.2rem;
      color: #d2691e;
    }
    footer {
      text-align: center;
      padding: 20px 0;
      background-color: #d2691e;
      color: white;
      margin-top: 40px;
      font-size: 1rem;
    }
  </style>
</head>
<body>
  <header>TayZa စားသောက်ဆိုင်</header>
  <nav>
    <a href="#home">ပင်မစာမျက်နှာ</a>
    <a href="#menu">မီနူး</a>
    <a href="#contact">ဆက်သွယ်ရန်</a>
  </nav>
  <main>
    <section id="home">
      <h2>ကြိုဆိုပါတယ်!</h2>
      <p>
        TayZa စားသောက်ဆိုင်တွင် ရိုးရာ မြန်မာအစားအစာများနှင့် မတူညီတဲ့ အရသာများကို
        ကြည့်ရှုခံစားနိုင်ပါတယ်။
      </p>
    </section>

    <section id="menu">
      <h2>မီနူး</h2>

      <div class="menu-item">
        <img src="https://images.unsplash.com/photo-1604908177527-ebc74e24b75a?auto=format&fit=crop&w=120&q=80" alt="လက်ဖက်တောင်း" />
        <div class="menu-info">
          <h3>လက်ဖက်တောင်း</h3>
          <p>တောင်သူလက်ဖက်ချပ်ပြားနဲ့ နှစ်သက်ဖို့ကောင်းတဲ့ ရိုးရာ အစားအစာ။</p>
        </div>
        <div class="menu-price">₭ 2500</div>
      </div>

      <div class="menu-item">
        <img src="https://images.unsplash.com/photo-1511688878353-21663ac68bc4?auto=format&fit=crop&w=120&q=80" alt="မုန့်ဟင်းခါး" />
        <div class="menu-info">
          <h3>မုန့်ဟင်းခါး</h3>
          <p>ဆူမြမြ စပ်စပ်လေးနဲ့ မုန့်ဟင်းခါး ထမင်းကြော်ပါ စားချင်တယ်။</p>
        </div>
        <div class="menu-price">₭ 3500</div>
      </div>

      <div class="menu-item">
        <img src="https://images.unsplash.com/photo-1547592180-16cdee0d1a42?auto=format&fit=crop&w=120&q=80" alt="အာလူးဟင်းလျာ" />
        <div class="menu-info">
          <h3>အာလူး ဟင်းလျာ</h3>
          <p>အာလူးသီးတွေနဲ့ စပ်စပ်ပေါင်းစပ်ထားတဲ့ ဟင်းလျာ။</p>
        </div>
        <div class="menu-price">₭ 2200</div>
      </div>
    </section>

    <section id="contact">
      <h2>ဆက်သွယ်ရန်</h2>
      <p>ဖုန်းနံပါတ်: 09 256315200</p>
      <p>အီးမေးလ်: tayzarko12@gmail.com</p>
      <p>လိပ်စာ: ဇလွန်မြို့၊ ဧရာဝတီတိုင်းဒေသကြီး</p>
    </section>
  </main>
  <footer>© 2024 TayZa စားသောက်ဆိုင်</footer>
</body>
</html>
