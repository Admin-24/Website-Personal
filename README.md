<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sewa Gitar & Drum Elektrik</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }

        header {
            background-color: #333;
            color: yellow;
            padding: 1em 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        nav ul {
            list-style: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            color: black;
            text-decoration: none;
        }

        /* Slider styles */
        .slider {
            width: 100%;
            overflow: hidden;
            position: relative;
            max-height: 400px;
        }

        .slides {
            display: flex;
            width: 65%; /* 100% per image */
            transition: transform 1s ease-in-out;
            animation: slideAnimation 10s infinite;
        }

        .slide {
            width: 130%;
            flex-shrink: 0;
        }

        .slide img {
            width: 95%;
            display: block;
        }

        @keyframes slideAnimation {
            0% { transform: translateX(0); }
            50% { transform: translateX(-100%); }
            100% { transform: translateX(0); }
        }

        .cta-button {
            background-color: #ff4b2b;
            color: white;
            padding: 15px 25px;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1.2em;
            margin-top: 20px;
            display: inline-block;
        }

        .cta-button:hover {
            background-color: #ff8c42;
        }

        section {
            padding: 40px 20px;
            text-align: center;
        }

        h2 {
            color: #333;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        ul li {
            background-color: #fff;
            padding: 8px;
            margin: 10px 0;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }

        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Music Rental 205</h1>
        <nav>
            <!-- You can add navigation here if needed -->
        </nav>
    </header>

    <section id="hero">
        <div class="slider">
            <div class="slides">
                <div class="slide">
                    <img src="IMG_20241023_145838.jpg" alt="Gambar Gitar">
                </div>
                <div class="slide">
                    <img src="IMG_20241023_145139.jpg" alt="Gambar Drum Elektrik">
                </div>
            </div>
        </div>
        <h2>Sewa Gitar & Drum Elektrik dengan Harga Terjangkau</h2>
        <p>Mainkan musik mulai dari 30NT!</p>
        <a href="#kontak" class="cta-button">Sewa Sekarang</a>
    </section>

    <section id="gitar">
        <h2>Paket Sewa Gitar</h2>
        <ul>
            <li>1 Hari: 30NT</li>
            <li>2 Hari: 50NT</li>
            <li>3 Hari: 75NT</li>
            <li>7 Hari: 150NT</li>
        </ul>
    </section>

    <section id="drum">
        <h2>Paket Sewa Drum Elektrik</h2>
        <ul>
            <li>1 Jam: 30NT</li>
            <li>2 Jam: 50NT</li>
        </ul>
    </section>

    <section id="kontak">
        <h2>Kontak Kami</h2>
        <p>WhatsApp: <a href="https://wa.me/+6289628806048">089628806048</a></p>
        <p>Line: <a href="https://line.me/ti/p/BqgmzRf0xM">@ky_104</a></p>
    </section>

    <footer>
        <p>Syarat dan ketentuan berlaku</p>
    </footer>
</body>
</html>
