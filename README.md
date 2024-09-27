<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PD MEKAR AGUNG - Kualitas Premium & Standar</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Roboto:wght@300;400&display=swap" rel="stylesheet">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/js/all.min.js"></script>
    <style>
        /* Existing styles remain unchanged */
        body, html {
            margin: 0;
            padding: 0;
            font-family: 'Roboto', sans-serif;
            background-color: #f8f8f8;
            color: #333;
        }
        .header {
            background-color: #2c3e50;
            color: #ecf0f1;
            text-align: center;
            padding: 2em;
        }
        .header h1 {
            font-family: 'Playfair Display', serif;
            font-size: 2.5em;
            margin: 0;
        }
        .nav {
            background-color: #34495e;
            padding: 1em 0;
            text-align: center;
        }
        .nav a {
            color: #ecf0f1;
            text-decoration: none;
            padding: 14px 20px;
            font-family: 'Playfair Display', serif;
            font-size: 1.1em;
            transition: all 0.3s ease;
        }
        .nav a:hover {
            background-color: #2c3e50;
        }
        .content {
            max-width: 1200px;
            margin: 0 auto;
            padding: 40px 20px;
        }
        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
        }
        .product {
            background-color: #fff;
            border: 1px solid #e0e0e0;
            padding: 20px;
            text-align: center;
            transition: all 0.3s ease;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        .product:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 12px rgba(0,0,0,0.15);
        }
        .product img {
            max-width: 100%;
            height: auto;
            margin-bottom: 15px;
        }
        .product h3 {
            font-family: 'Playfair Display', serif;
            margin-bottom: 10px;
        }
        .buy-btn {
            background-color: #2c3e50;
            color: #ecf0f1;
            padding: 10px 20px;
            text-decoration: none;
            display: inline-block;
            margin-top: 10px;
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
        }
        .buy-btn:hover {
            background-color: #34495e;
        }
        .section-title {
            font-family: 'Playfair Display', serif;
            text-align: center;
            margin-bottom: 30px;
            color: #2c3e50;
        }
        .info-section {
            background-color: #fff;
            padding: 40px;
            margin-top: 40px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        /* New styles for product categories */
        .product-category {
            margin-bottom: 60px;
        }
        .category-title {
            font-family: 'Playfair Display', serif;
            text-align: center;
            margin-bottom: 30px;
            color: #2c3e50;
            font-size: 1.8em;
            position: relative;
        }
        .category-title::after {
            content: '';
            display: block;
            width: 50px;
            height: 3px;
            background-color: #2c3e50;
            margin: 10px auto;
        }
        /* Existing contact styles remain unchanged */
    </style>
</head>
<body>
    <div class="header">
        <h1>PD MEKAR AGUNG</h1>
        <p>Kualitas Premium dan Standar untuk Rumah Anda</p>
    </div>

    <div class="nav">
        <a href="#beranda">Beranda</a>
        <a href="#tempat">Lokasi</a>
        <a href="#kontak">Hubungi Kami</a>
    </div>

    <div class="content">
        <div id="beranda">
            <h2 class="section-title">Koleksi Produk Kami</h2>
            
            <div class="product-category">
                <h3 class="category-title">Produk Eksklusif</h3>
                <div class="product-grid">
                    <div class="product">
                        <img src="/api/placeholder/400/300" alt="Pintu Kayu Mewah">
                        <h3>Pintu Kayu Mewah</h3>
                        <p>Pintu kayu solid dengan ukiran elegan</p>
                        <a href="https://wa.me/628128061052?text=Saya%20tertarik%20dengan%20Pintu%20Kayu%20Mewah" class="buy-btn">Pesan Sekarang</a>
                    </div>
                    <div class="product">
                        <img src="/api/placeholder/400/300" alt="Kusen Kayu Premium">
                        <h3>Kusen Kayu Premium</h3>
                        <p>Kusen kayu berkualitas tinggi dengan finishing sempurna</p>
                        <a href="https://wa.me/628128061052?text=Saya%20tertarik%20dengan%20Kusen%20Kayu%20Premium" class="buy-btn">Pesan Sekarang</a>
                    </div>
                    <div class="product">
                        <img src="/api/placeholder/400/300" alt="Pintu Aluminium Modern">
                        <h3>Pintu Aluminium Modern</h3>
                        <p>Desain kontemporer dengan teknologi terkini</p>
                        <a href="https://wa.me/628128061052?text=Saya%20tertarik%20dengan%20Pintu%20Aluminium%20Modern" class="buy-btn">Pesan Sekarang</a>
                    </div>
                    <div class="product">
                        <img src="/api/placeholder/400/300" alt="Kusen Aluminium Elegan">
                        <h3>Kusen Aluminium Elegan</h3>
                        <p>Perpaduan sempurna antara estetika dan durabilitas</p>
                        <a href="https://wa.me/628128061052?text=Saya%20tertarik%20dengan%20Kusen%20Aluminium%20Elegan" class="buy-btn">Pesan Sekarang</a>
                    </div>
                </div>
            </div>
            
            <div class="product-category">
                <h3 class="category-title">Produk Standar</h3>
                <div class="product-grid">
                    <div class="product">
                        <img src="/api/placeholder/400/300" alt="Pintu Kayu Standar">
                        <h3>Pintu Kayu Standar</h3>
                        <p>Pintu kayu fungsional dengan harga terjangkau</p>
                        <a href="https://wa.me/628128061052?text=Saya%20tertarik%20dengan%20Pintu%20Kayu%20Standar" class="buy-btn">Pesan Sekarang</a>
                    </div>
                    <div class="product">
                        <img src="/api/placeholder/400/300" alt="Kusen Kayu Biasa">
                        <h3>Kusen Kayu Biasa</h3>
                        <p>Kusen kayu sederhana untuk kebutuhan umum</p>
                        <a href="https://wa.me/628128061052?text=Saya%20tertarik%20dengan%20Kusen%20Kayu%20Biasa" class="buy-btn">Pesan Sekarang</a>
                    </div>
                    <div class="product">
                        <img src="/api/placeholder/400/300" alt="Pintu Aluminium Standar">
                        <h3>Pintu Aluminium Standar</h3>
                        <p>Pintu aluminium praktis untuk penggunaan sehari-hari</p>
                        <a href="https://wa.me/628128061052?text=Saya%20tertarik%20dengan%20Pintu%20Aluminium%20Standar" class="buy-btn">Pesan Sekarang</a>
                    </div>
                    <div class="product">
                        <img src="/api/placeholder/400/300" alt="Kusen Aluminium Biasa">
                        <h3>Kusen Aluminium Biasa</h3>
                        <p>Kusen aluminium sederhana namun tahan lama</p>
                        <a href="https://wa.me/628128061052?text=Saya%20tertarik%20dengan%20Kusen%20Aluminium%20Biasa" class="buy-btn">Pesan Sekarang</a>
                    </div>
                </div>
            </div>
        </div>

        <!-- Existing Location and Contact sections remain unchanged -->
        <div id="tempat" class="info-section">
            <h2 class="section-title">Lokasi Kami</h2>
            <p>PD MEKAR AGUNG berkomitmen untuk memberikan pengalaman berbelanja yang eksklusif. Kunjungi showroom kami di:</p>
            <p>Jln. Maulana Hasanudin No. 55, RT 03 RW 03</p>
            <p>Poris Jaya, Batuceper, Kota Tangerang</p>
        </div>

        <div id="kontak" class="info-section">
            <h2 class="section-title">Hubungi Kami</h2>
            <p>Kami siap membantu Anda menemukan produk sempurna untuk rumah Anda. Jangan ragu untuk menghubungi kami.</p>
            
            <div class="contact-grid">
                <div class="contact-card">
                    <div class="contact-icon"><i class="fas fa-user-tie"></i></div>
                    <h3 class="contact-title">Owner</h3>
                    <p class="contact-info">WhatsApp: 08128061052</p>
                    <a href="https://wa.me/628128061052" class="contact-link">Hubungi Owner</a>
                </div>
                
                <div class="contact-card">
                    <div class="contact-icon"><i class="fas fa-headset"></i></div>
                    <h3 class="contact-title">Admin</h3>
                    <p class="contact-info">WhatsApp: 081295728972</p>
                    <a href="https://wa.me/6281295728972" class="contact-link">Hubungi Admin</a>
                </div>
                
                <div class="contact-card">
                    <div class="contact-icon"><i class="fas fa-envelope"></i></div>
                    <h3 class="contact-title">Email</h3>
                    <p class="contact-info">customercare@pdmekaragung.com</p>
                    <a href="mailto:customercare@pdmekaragung.com" class="contact-link">Kirim Email</a>
                </div>
            </div>
        </div>
    </div>

    <script>
        // JavaScript bisa ditambahkan di sini untuk fungsionalitas tambahan
    </script>
</body>
</html>
