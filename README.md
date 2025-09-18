<!DOCTYPE html>
<html lang="my">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>စားသောက်ဆိုင်</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>စားသောက်ဆိုင်</h1>
            <nav>
                <ul>
                    <li><a href="#home">ပင်မစာမျက်နှာ</a></li>
                    <li><a href="#menu">မီနူး</a></li>
                    <li><a href="#about">ကျွန်တော်တို့အကြောင်း</a></li>
                    <li><a href="#contact">ဆက်သွယ်ရန်</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home">
        <h2>ကြိုဆိုပါတယ်!</h2>
        <p>အရသာအထူးများနဲ့ သောက်စားရန်အတွက် ဆိုင်သစ်မှ ကြိုဆိုပါတယ်။</p>
    </section>

    <section id="menu">
        <h2>မီနူး</h2>
        <div class="menu-items">
            <div class="item">
                <img src="https://source.unsplash.com/300x200/?burger" alt="Burger">
                <h3>Burger</h3>
                <p>ကောင်းမွန်တဲ့ အရသာနဲ့ အသားပြည့် Burger</p>
            </div>
            <div class="item">
                <img src="https://source.unsplash.com/300x200/?pizza" alt="Pizza">
                <h3>Pizza</h3>
                <p>အရသာမြောက် Pizza</p>
            </div>
            <div class="item">
                <img src="https://source.unsplash.com/300x200/?noodle" alt="Noodles">
                <h3>Noodles</h3>
                <p>အနွေးအေးကြိုက် Noodles</p>
            </div>
        </div>
    </section>

    <section id="about">
        <h2>ကျွန်တော်တို့အကြောင်း</h2>
        <p>စားသောက်ဆိုင်ကို ၂၀၁၅ ခုနှစ်တွင် စတင်တည်ထောင်ခဲ့ပြီး အရသာကောင်းပြီး ဝန်ဆောင်မှုမြန်ဆန်ပါတယ်။</p>
    </section>

    <section id="contact">
        <h2>ဆက်သွယ်ရန်</h2>
        <form>
            <input type="text" placeholder="အမည်" required>
            <input type="email" placeholder="အီးမေးလ်" required>
            <textarea placeholder="မက်ဆေ့ခ်ျ" required></textarea>
            <button type="submit">ပို့မည်</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 စားသောက်ဆိုင်</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #ff6347;
    color: white;
    padding: 20px 0;
}

header .container {
    width: 90%;
    margin: auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    padding: 50px 0;
    text-align: center;
}

.menu-items {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}

.item {
    width: 300px;
    border: 1px solid #ccc;
    padding: 10px;
}

.item img {
    width: 100%;
    height: auto;
}

form {
    display: flex;
    flex-direction: column;
    gap: 10px;
    width: 300px;
    margin: auto;
}

input, textarea {
    padding: 10px;
    width: 100%;
    box-sizing: border-box;
}

button {
    padding: 10px;
    background-color: #ff6347;
    color: white;
    border: none;
    cursor: pointer;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
}