 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Prime cineplex">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
    <title>Document</title>
    <link rel="stylesheet" href="index.css">
    <script>
        document.addEventListener('scroll', () => {
            const nav = document.querySelector('nav');
            if(window.scrollY > 100 ){
                nav.classList.add('scrolled');
            }
            else{
                nav.classList.remove('scrolled');
            }
        })
    </script>
    <style>
video{
    width: 100%;
    position: relative;
    background-position: center;
    background-size: cover;
} 
    </style>
</head>
<body>
    <nav>
        <img src="./source/logo.jpg" alt="">
        <a href="index.html">Захиалах</a>
        <a href="index.html">Тун удахгүй</a>
        <a href="index.html">Бүртгүүлэх</a>
        <a href="index.html">Миний бүртгэл</a>
    </nav>
<section >
    <video src="./source/bgvid.mp4" autoplay loop muted ></video>
    <div id="infobtn">
         <a class="order-btn" href="index.html">Захиалах</a>
         <a class="order-btn" href="index.html" style="left: 25%;">Дэлгэрэнгүй</a>
    </div>
</section>
<section >
    <article id="page2">
        <h2 id="md" >Манай дэлгэцнээ</h2>
    <div class="container">
        <img src="./source/download.jpg" alt="">
        <img src="./source/download.jpg" alt="">
        <img src="./source/download.jpg" alt="">
        <img src="./source/download.jpg" alt="">
        <img src="./source/download.jpg" alt="">
        <img src="./source/download.jpg" alt="">
        <img src="./source/download.jpg" alt="">
        <img src="./source/download.jpg" alt="">
        <img src="./source/download.jpg" alt="">
        <img src="./source/download.jpg" alt="">
        <img src="./source/download.jpg" alt="">
        <img src="./source/download.jpg" alt="">
    </div>
    <div id="button">
    <a href="index.html">Бүгдийг харах</a>
    <a href="index.html">Захиалах</a>
</div>
    </article>
    
</section>
<section>
    <article id="page3">
    <h2>Тун удахгүй</h2>
    <article > <h3>Онцлох</h3>
        <img src="./source/download.jpg" alt="" >
        <button>Дэлгэрэнгүй</button>
    </article>
        <h3>Бусад</h3>
    <img src="./source/download.jpg" alt="" >
    <img src="./source/download.jpg" alt="" >
    <img src="./source/download.jpg" alt="" >
    <div class="btn">
    <a href="index.html">Бүгдийг харах</a>
    <a href="index.html">Урьдчилан захиалах</a>
</div>
</article>
</section>
<section>
    <article id="page4">
    <h2>Нэмэлт</h2>
    <div class="btn">
    <a href="arcade.html">Arcade</a>
    <a href="Snack.html">Амттан</a>
</div>
    <article>
        <h3>Санал хүсэлт</h3>
        <form action="/action_page.php">
            <input type="text"  id="setgegdel" value="">
            <label for="setgegdel">Сэтгэгдэл</label><br>
            <input type="email"  id="email" value="">
            <label for="email">Email</label><br>
          </form>
        <button>Илгээх</button>
    </article>
</article>
    <address>
    Байршил <br>
    Холбогдох утас <br>
    Холбогдох и-мейл
    </address>

        
  
    <footer>Copyright2024</footer>
</section>
</body>

</html>
