<!DOCTYPE html>
<html lang="my">
<head>
    <meta charset="UTF-8">
    <title>TAY ZA - Personal Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<!-- Navbar -->
<nav class="navbar">
    <div class="container">
        <h1 class="logo">TAY ZA</h1>
        <ul class="nav-links">
            <li><a href="#home">ပင်မ</a></li>
            <li><a href="#about">အကြောင်း</a></li>
            <li><a href="#gallery">Gallery</a></li>
            <li><a href="#contact">ဆက်သွယ်ရန်</a></li>
        </ul>
    </div>
</nav>

<!-- Hero -->
<header id="home" class="hero">
    <div class="container">
        <img src="tay.jpg" class="profile-img">
        <h2>မင်္ဂလာပါ၊ ကျွန်တော် တေဇ ပါ</h2>
        <p>Web Developer & Designer</p>
        <a href="#contact" class="btn">ဆက်သွယ်ရန်</a>
    </div>
</header>

<!-- About -->
<section id="about" class="container">
    <div class="card">
        <h2>ကျွန်တော့်အကြောင်း</h2>
        <p>
            ကျွန်တော်သည် Website ဖန်တီးခြင်းကို ဝါသနာပါသူတစ်ဦးဖြစ်ပြီး  
            HTML, CSS, Python တို့ကို အသုံးပြုပြီး Project များလုပ်နေပါသည်။
        </p>
    </div>
</section>

<!-- Gallery -->
<section id="gallery" class="container">
    <div class="card">
        <h2>Gallery (ပုံ ၁၀ ပုံ)</h2>
        <div class="gallery">
            <img src="img1.jpg">
            <img src="img2.jpg">
            <img src="img3.jpg">
            <img src="img4.jpg">
            <img src="img5.jpg">
            <img src="img6.jpg">
            <img src="img7.jpg">
            <img src="img8.jpg">
            <img src="img9.jpg">
            <img src="img10.jpg">
        </div>
    </div>
</section>

<!-- Contact -->
<section id="contact" class="container">
    <div class="card">
        <h2>ဆက်သွယ်ရန်</h2>
        <p>📧 Email: tayzarko12@gmail.com</p>
        <p>📞 Phone: 09-256315200</p>
    </div>
</section>

<!-- Footer -->
<footer>
    <p>© 2024 TAY ZA | Personal Website</p>
</footer>

</body>
</html>      margin-bottom: 20px;
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
