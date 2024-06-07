<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Homepage Promosi</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #F0F8FF;
            color: #333;
        }
        header {
            background-color: #FFD700;
            color: #333;
            text-align: center;
            padding: 20px 0;
        }
        nav {
            background-color: #20B2AA;
            color: #fff;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
        }
        .content {
            padding: 20px;
        }
        .gallery img {
            width: 100%;
            height: auto;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        .gallery img {
            flex: 1 1 calc(33.333% - 20px);
            box-sizing: border-box;
        }
        .form-container {
            max-width: 600px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            border: 1px solid #ccc;
            border-radius: 10px;
        }
        .form-container input, .form-container textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .form-container button {
            background-color: #FFD700;
            color: #333;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .form-container button:hover {
            background-color: #FFC107;
        }
        footer {
            background-color: #20B2AA;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Selamat Datang di Halaman Promosi Saya</h1>
    </header>
    <nav>
        <a href="#about">Tentang Saya</a>
        <a href="#gallery">Galeri</a>
        <a href="#contact">Kontak</a>
    </nav>
    <div class="content" id="about">
        <h2>Tentang Saya</h2>
        <p>Halo! Saya [Nama Anda], seorang [Profesi/Kegiatan]. Selamat datang di halaman promosi saya. Di sini Anda dapat menemukan informasi tentang pekerjaan saya, melihat portofolio saya, dan menghubungi saya untuk kolaborasi atau pertanyaan lebih lanjut.</p>
    </div>
    <div class="content" id="gallery">
        <h2>Galeri Foto</h2>
        <div class="gallery">
            <img src="https://via.placeholder.com/300" alt="Foto 1">
            <img src="https://via.placeholder.com/300" alt="Foto 2">
            <img src="https://via.placeholder.com/300" alt="Foto 3">
            <img src="https://via.placeholder.com/300" alt="Foto 4">
            <img src="https://via.placeholder.com/300" alt="Foto 5">
            <img src="https://via.placeholder.com/300" alt="Foto 6">
        </div>
    </div>
    <div class="content" id="contact">
        <h2>Kontak</h2>
        <div class="form-container">
            <form action="mailto:youremail@example.com" method="post" enctype="text/plain">
                <label for="name">Nama:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Pesan:</label>
                <textarea id="message" name="message" rows="4" required></textarea>
                <button type="submit">Kirim</button>
            </form>
        </div>
        <p>Anda juga dapat mengikuti saya di media sosial:</p>
        <p>
            <a href="https://www.facebook.com" target="_blank">Facebook</a> | 
            <a href="https://www.twitter.com" target="_blank">Twitter</a> | 
            <a href="https://www.instagram.com" target="_blank">Instagram</a>
        </p>
        <p>Kunjungi website saya: <a href="https://www.yourwebsite.com" target="_blank">www.yourwebsite.com</a></p>
    </div>
    <footer>
        <p>&copy; 2024 [Nama Anda]. All rights reserved.</p>
    </footer>
</body>
</html>
