<!DOCTYPE html>
<html lang="hu">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Személyes Blogom és Bögre Nyomtatás</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f7f7f7;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #ff6f61;
            color: white;
            text-align: center;
            padding: 2rem;
        }

        header h1 {
            margin: 0;
            font-size: 3rem;
        }

        nav {
            background-color: #ffcc5c;
            padding: 1rem;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
            font-weight: bold;
        }

        section {
            padding: 2rem;
        }

        h2 {
            color: #ff6f61;
            font-size: 2rem;
        }

        .intro {
            background-color: #ffeead;
            padding: 2rem;
            border-radius: 10px;
            margin-bottom: 2rem;
        }

        .intro p {
            font-size: 1.2rem;
            line-height: 1.6;
        }

        .blog, .mugs {
            margin-bottom: 3rem;
        }

        .blog-post {
            background-color: #88d8b0;
            padding: 1.5rem;
            margin-bottom: 1rem;
            border-radius: 10px;
        }

        .mug-gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
        }

        .mug-gallery img {
            width: 200px;
            height: 200px;
            object-fit: cover;
            border-radius: 10px;
        }

        footer {
            background-color: #ff6f61;
            color: white;
            text-align: center;
            padding: 1rem;
            margin-top: 2rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>Személyes Blogom és Bögre Nyomtatás</h1>
    </header>

    <nav>
        <a href="#about">Rólam</a>
        <a href="#blog">Blog</a>
        <a href="#mugs">Bögre Nyomtatás</a>
        <a href="#contact">Kapcsolat</a>
    </nav>

    <section id="about">
        <h2>Rólam</h2>
        <div class="intro">
            <p>Sziasztok! [A Te neved] vagyok, és szenvedélyem a kreatív tervezés és bögre nyomtatás. Ezen a blogon megosztom a legújabb gondolataimat, projektjeimet, és bemutatom a színes bögre nyomtatási munkáimat. Szeretem a vidám és élénk dizájnokat, így bármilyen különleges ötleted van, nyugodtan keress fel!</p>
        </div>
    </section>

    <section id="blog" class="blog">
        <h2>Blog</h2>
        <div class="blog-post">
            <h3>Első bejegyzésem</h3>
            <p>Ebben a bejegyzésben bemutatom, hogyan készítem el a legújabb bögrenyomataimat. Nagyon izgalmas látni, ahogy az elképzelések életre kelnek!</p>
        </div>
        <div class="blog-post">
            <h3>Inspiráció a mindennapokban</h3>
            <p>Az inspiráció sok helyről érkezhet: természet, színek, emberek. Íme néhány gondolat, ami segített a legutóbbi munkáim elkészítésében.</p>
        </div>
    </section>

    <section id="mugs" class="mugs">
        <h2>Bögre Nyomtatás</h2>
        <div class="mug-gallery">
            <img src="mug1.jpg" alt="Nyomtatott bögre 1">
            <img src="mug2.jpg" alt="Nyomtatott bögre 2">
            <img src="mug3.jpg" alt="Nyomtatott bögre 3">
            <img src="mug4.jpg" alt="Nyomtatott bögre 4">
        </div>
    </section>

    <footer id="contact">
        <p>Kapcsolat: [email@example.com]</p>
    </footer>

</body>
</html>
