<!DOCTYPE html>
<html>
<head>
    <title>Dunia Imajinasi Artana - Dark</title>
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', sans-serif;
            color: white;
            background: url('https://images.unsplash.com/photo-1534447677768-be436bb09401') no-repeat center center fixed;
            background-size: cover;
        }

        header {
            text-align: center;
            padding: 30px;
            font-size: 32px;
            background: rgba(0,0,0,0.6);
            letter-spacing: 2px;
        }

        nav {
            text-align: center;
            background: rgba(0,0,0,0.7);
            padding: 15px;
        }

        nav a {
            color: #d4bfff;
            margin: 15px;
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
        }

        nav a:hover {
            color: white;
            text-shadow: 0 0 10px #c77dff;
        }

        section {
            padding: 50px;
            background: rgba(0,0,0,0.6);
            margin: 20px;
            border-radius: 15px;
        }

        .gallery img {
            width: 220px;
            height: 220px;
            margin: 15px;
            border-radius: 15px;
            object-fit: cover;
            transition: 0.5s;
        }

        .gallery img:hover {
            transform: scale(1.1);
            box-shadow: 0 0 20px #c77dff;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: rgba(0,0,0,0.7);
            font-size: 14px;
        }

        .music-control {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background: rgba(0,0,0,0.7);
            padding: 10px;
            border-radius: 50%;
            cursor: pointer;
            font-size: 20px;
        }
    </style>
</head>

<body>

<header>
    🌙 Dunia Imajinasi Artana 🌙
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#gallery">Galeri</a>
    <a href="#about">Tentang</a>
</nav>

<section id="home">
    <h2>Selamat Datang di Dunia Malamku</h2>
    <p>Di bawah langit gelap penuh bintang, imajinasi hidup.</p>
</section>

<section id="gallery">
    <h2>Galeri Imajinasi</h2>
    <div class="gallery">
        <img src="https://picsum.photos/300?dark1">
        <img src="https://picsum.photos/300?dark2">
        <img src="https://picsum.photos/300?dark3">
    </div>
</section>

<section id="about">
    <h2>Tentang Artana</h2>
    <p>Aku Artana.</p>
    <p>Website ini adalah ruang gelap penuh cahaya kecil dari mimpiku.</p>
</section>

<footer>
    © 2026 Artana | Dark Aesthetic
</footer>

<!-- AUTOPLAY MUSIC -->
<audio id="bg-music" autoplay loop>
    <source src="https://www.bensound.com/bensound-music/bensound-slowmotion.mp3" type="audio/mp3">
</audio>

<div class="music-control" onclick="toggleMusic()">🎵</div>

<script>
    var music = document.getElementById("bg-music");

    function toggleMusic() {
        if (music.paused) {
            music.play();
        } else {
            music.pause();
        }
    }
</script>

</body>
</html>
