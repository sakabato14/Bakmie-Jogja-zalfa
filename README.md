<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Website Resmi Bakmie Jogja Zalfa. Nikmati Bakmie Godog dan Goreng asli dengan ayam kampung yang dimasak menggunakan anglo arang kayu. Cabang Cirendeu, Rempoa, dan Bojongsari.">
    <meta name="keywords" content="Bakmie Jogja, Bakmie Godog, Kuliner Cirendeu, Kuliner Rempoa, Bakmie Ayam Kampung, Makan Malam Keluarga">
    <meta name="author" content="Bakmie Jogja Zalfa Digital Team">
    
    <meta property="og:title" content="Bakmie Jogja Zalfa - Cita Rasa Asli Anglo">
    <meta property="og:description" content="Spesialis Bakmie Jawa dengan Ayam Kampung Asli. Buka Setiap Hari jam 16:00.">
    <meta property="og:type" content="restaurant">
    
    <title>Bakmie Jogja Zalfa | Spesialis Ayam Kampung & Masak Anglo</title>
    
    <style>
        /* --- CSS VARIABLES & RESET --- */
        :root {
            --primary-orange: #d35400; /* Warna Api/Bumbu Pedas */
            --primary-dark: #a04000;
            --secondary-charcoal: #2c3e50; /* Warna Arang/Anglo */
            --bg-cream: #f9f7f2; /* Warna Alami/Vintage */
            --text-dark: #333333;
            --text-light: #ecf0f1;
            --accent-green: #27ae60; /* Indikator Buka */
            --accent-red: #c0392b; /* Indikator Tutup */
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: 'Segoe UI', 'Roboto', 'Helvetica Neue', sans-serif;
            background-color: var(--bg-cream);
            color: var(--text-dark);
            line-height: 1.6;
        }

        /* --- TYPOGRAPHY --- */
        h1, h2, h3 {
            font-weight: 700;
            color: var(--secondary-charcoal);
        }

        h2 {
            text-align: center;
            font-size: 2.2rem;
            margin-bottom: 2.5rem;
            position: relative;
            padding-bottom: 15px;
        }

        h2::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 80px;
            height: 4px;
            background-color: var(--primary-orange);
            border-radius: 2px;
        }

        /* --- HEADER & NAV --- */
        header {
            background-color: var(--secondary-charcoal);
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            position: sticky;
            top: 0;
            z-index: 1000;
        }

       .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 0 20px;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            height: 70px;
        }

       .brand-logo {
            font-size: 1.5rem;
            font-weight: 800;
            color: var(--primary-orange);
            text-transform: uppercase;
            letter-spacing: 1px;
            text-decoration: none;
        }

       .brand-logo span {
            color: #fff;
        }

       .nav-menu {
            display: flex;
            gap: 25px;
        }

       .nav-menu a {
            color: #ccc;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
            font-size: 0.95rem;
        }

       .nav-menu a:hover {
            color: var(--primary-orange);
        }

        /* --- HERO SECTION --- */
       .hero {
            position: relative;
            height: 70vh;
            min-height: 500px;
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.6)), url('https://placehold.co/1200x800/222/d35400?text=Bakmie+Jogja+Anglo+Fire');
            background-size: cover;
            background-position: center;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: #fff;
        }

       .hero-content h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
            color: #fff;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
        }

       .hero-content p {
            font-size: 1.25rem;
            margin-bottom: 2rem;
            max-width: 700px;
            margin-left: auto;
            margin-right: auto;
        }

       .cta-button {
            display: inline-block;
            background-color: var(--primary-orange);
            color: white;
            padding: 15px 35px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.1rem;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(211, 84, 0, 0.4);
        }

       .cta-button:hover {
            background-color: var(--primary-dark);
            transform: translateY(-2px);
        }

        /* --- FEATURES / USP --- */
       .features {
            padding: 3rem 0;
            background-color: #fff;
            text-align: center;
        }

       .feature-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
        }

       .feature-item i {
            font-size: 2rem;
            color: var(--primary-orange);
            margin-bottom: 1rem;
        }

       .feature-item h3 {
            margin-bottom: 0.5rem;
            font-size: 1.2rem;
        }

        /* --- MENU SECTION --- */
        section {
            padding: 5rem 0;
        }

       .menu-category {
            margin-bottom: 3rem;
        }

       .menu-category h3 {
            font-size: 1.5rem;
            border-left: 5px solid var(--primary-orange);
            padding-left: 15px;
            margin-bottom: 1.5rem;
            color: var(--secondary-charcoal);
        }

       .menu-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
            gap: 25px;
        }

       .menu-card {
            background: #fff;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
            transition: transform 0.3s;
            border: 1px solid #eee;
        }

       .menu-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 25px rgba(0,0,0,0.1);
        }

       .menu-body {
            padding: 1.5rem;
        }

       .menu-header {
            display: flex;
            justify-content: space-between;
            align-items: baseline;
            margin-bottom: 10px;
            border-bottom: 1px dashed #ddd;
            padding-bottom: 10px;
        }

       .menu-title {
            font-weight: 700;
            font-size: 1.15rem;
            color: var(--secondary-charcoal);
        }

       .menu-price {
            font-weight: 700;
            color: var(--primary-orange);
            font-size: 1.1rem;
            white-space: nowrap;
        }

       .menu-desc {
            font-size: 0.9rem;
            color: #666;
            margin-bottom: 15px;
            line-height: 1.5;
        }

       .badge {
            display: inline-block;
            padding: 4px 10px;
            border-radius: 4px;
            font-size: 0.75rem;
            font-weight: 600;
            margin-top: 5px;
        }

       .badge-best { background-color: #fce4ec; color: #c2185b; }
       .badge-recom { background-color: #e8f5e9; color: #2e7d32; }

        /* --- LOCATIONS & HOURS --- */
       .info-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 3rem;
        }

       .location-list {
            display: flex;
            flex-direction: column;
            gap: 1.5rem;
        }

       .location-card {
            background: #fff;
            padding: 1.5rem;
            border-radius: 10px;
            border-left: 5px solid var(--secondary-charcoal);
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
        }

       .location-card h4 {
            font-size: 1.2rem;
            margin-bottom: 0.5rem;
            color: var(--primary-orange);
        }

       .hours-box {
            background-color: var(--secondary-charcoal);
            color: white;
            padding: 2.5rem;
            border-radius: 15px;
            text-align: center;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }

       .status-indicator {
            font-size: 1.5rem;
            font-weight: bold;
            margin: 1rem 0;
            padding: 10px;
            border-radius: 8px;
            display: inline-block;
        }

       .open { background-color: var(--accent-green); }
       .closed { background-color: var(--accent-red); }

        /* --- FOOTER --- */
        footer {
            background-color: #1a252f;
            color: #7f8c8d;
            padding: 3rem 0;
            text-align: center;
            font-size: 0.9rem;
        }

       .social-links {
            margin-bottom: 1.5rem;
        }

       .social-links a {
            color: white;
            font-size: 1.5rem;
            margin: 0 10px;
            text-decoration: none;
            transition: color 0.3s;
        }

       .social-links a:hover {
            color: var(--primary-orange);
        }

        /* --- RESPONSIVE --- */
        @media (max-width: 768px) {
           .hero-content h1 { font-size: 2rem; }
           .nav-menu { display: none; } /* Mobile Menu would need JS */
           .info-grid { grid-template-columns: 1fr; }
           .location-card { text-align: left; }
        }
    </style>
</head>
<body>

    <header>
        <div class="container">
            <nav>
                <a href="#" class="brand-logo">Bakmie<span>JogjaZalfa</span></a>
                <div class="nav-menu">
                    <a href="#tentang">Tentang Kami</a>
                    <a href="#menu">Menu & Harga</a>
                    <a href="#lokasi">Lokasi Cabang</a>
                    <a href="#kontak">Kontak</a>
                </div>
            </nav>
        </div>
    </header>

    <div class="hero">
        <div class="container hero-content">
            <h1>Kehangatan Asli Jogja di Selatan Jakarta</h1>
            <p>Sajian Bakmie Godog dan Goreng otentik dengan <strong>Ayam Kampung</strong> pilihan. Dimasak perlahan menggunakan <strong>Anglo dan Arang Kayu</strong> untuk cita rasa smoky yang melegenda.</p>
            <a href="#menu" class="cta-button">Lihat Menu Favorit</a>
        </div>
    </div>

    <div class="features">
        <div class="container">
            <div class="feature-grid">
                <div class="feature-item">
                    <h3>🔥 Masak Anglo</h3>
                    <p>Dimasak satu per satu menggunakan tungku tanah liat dan arang kayu.</p>
                </div>
                <div class="feature-item">
                    <h3>🐔 Ayam Kampung</h3>
                    <p>Hanya menggunakan suwiran ayam kampung asli, bukan ayam negeri.</p>
                </div>
                <div class="feature-item">
                    <h3>🍲 Resep Warisan</h3>
                    <p>Kaldu ayam kental yang dimasak berjam-jam untuk rasa yang dalam.</p>
                </div>
            </div>
        </div>
    </div>

    <section id="menu">
        <div class="container">
            <h2>Daftar Menu & Harga</h2>
            
            <div class="menu-category">
                <h3>Hidangan Utama (Bakmie & Nasi)</h3>
                <div class="menu-grid">
                    <div class="menu-card">
                        <div class="menu-body">
                            <div class="menu-header">
                                <span class="menu-title">Bakmie Godog</span>
                                <span class="menu-price">Rp 36.000</span>
                            </div>
                            <p class="menu-desc">Mie kuning rebus dengan kuah kaldu kental, sayuran, telur bebek/ayam, dan suwiran ayam kampung.</p>
                            <span class="badge badge-best">Terlaris</span>
                        </div>
                    </div>
                    <div class="menu-card">
                        <div class="menu-body">
                            <div class="menu-header">
                                <span class="menu-title">Bakmie Goreng</span>
                                <span class="menu-price">Rp 36.000</span>
                            </div>
                            <p class="menu-desc">Mie kuning goreng nyemek/kering dengan bumbu kecap manis gurih, sayuran, dan ayam kampung. Aroma gosong (smoky) khas anglo.</p>
                            <span class="badge badge-recom">Favorit</span>
                        </div>
                    </div>
                    <div class="menu-card">
                        <div class="menu-body">
                            <div class="menu-header">
                                <span class="menu-title">Magelangan (Nasi Mawut)</span>
                                <span class="menu-price">Rp 36.000</span>
                            </div>
                            <p class="menu-desc">Kombinasi mengenyangkan antara Nasi dan Mie yang dimasak bersamaan (Godog/Goreng). Porsi mantap.</p>
                        </div>
                    </div>
                    <div class="menu-card">
                        <div class="menu-body">
                            <div class="menu-header">
                                <span class="menu-title">Nasi Goreng Jawa</span>
                                <span class="menu-price">Rp 33.000</span>
                            </div>
                            <p class="menu-desc">Nasi goreng bumbu ulek tradisional (bawang & kemiri) dengan suwiran ayam kampung.</p>
                        </div>
                    </div>
                    <div class="menu-card">
                        <div class="menu-body">
                            <div class="menu-header">
                                <span class="menu-title">Bihun (Godog/Goreng)</span>
                                <span class="menu-price">Rp 36.000</span>
                            </div>
                            <p class="menu-desc">Alternatif bihun beras yang lembut, dimasak dengan metode yang sama dengan bakmie.</p>
                        </div>
                    </div>
                    <div class="menu-card">
                        <div class="menu-body">
                            <div class="menu-header">
                                <span class="menu-title">Nasi Godog</span>
                                <span class="menu-price">Rp 33.000</span>
                            </div>
                            <p class="menu-desc">Nasi yang direbus dalam kuah kaldu berbumbu. Hangat dan nyaman di perut.</p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="menu-category">
                <h3>Minuman & Dessert Tradisional</h3>
                <div class="menu-grid">
                    <div class="menu-card">
                        <div class="menu-body">
                            <div class="menu-header">
                                <span class="menu-title">Wedang Ronde</span>
                                <span class="menu-price">Rp 20.000</span>
                            </div>
                            <p class="menu-desc">Minuman jahe hangat dengan isian ronde ketan, kolang-kaling, kacang sangrai, dan roti tawar.</p>
                            <span class="badge badge-best">Signature</span>
                        </div>
                    </div>
                    <div class="menu-card">
                        <div class="menu-body">
                            <div class="menu-header">
                                <span class="menu-title">Jeruk Murni (Panas/Es)</span>
                                <span class="menu-price">Rp 15.000</span>
                            </div>
                            <p class="menu-desc">Sari jeruk peras asli, menyegarkan tenggorokan.</p>
                        </div>
                    </div>
                    <div class="menu-card">
                        <div class="menu-body">
                            <div class="menu-header">
                                <span class="menu-title">Teh Manis / Tawar</span>
                                <span class="menu-price">Rp 5rb - 10rb</span>
                            </div>
                            <p class="menu-desc">Teh seduh wangi melati. Tersedia panas atau dingin.</p>
                        </div>
                    </div>
                </div>
            </div>
            
            <p style="text-align: center; color: #777; font-size: 0.9rem; margin-top: 20px;">*Harga dapat berubah sewaktu-waktu. Harga di aplikasi online mungkin berbeda.</p>
        </div>
    </section>

    <section id="lokasi" style="background-color: #fff;">
        <div class="container">
            <h2>Lokasi & Jam Buka</h2>
            
            <div class="info-grid">
                <div class="location-list">
                    <div class="location-card">
                        <h4>📍 Cabang Cirendeu (Pusat)</h4>
                        <p>Jl. Raya Cirendeu, Tangerang Selatan</p>
                        <p style="font-size: 0.9rem; color: #666; margin-top: 5px;">Cabang dengan rating tertinggi dan terfavorit.</p>
                        <div style="margin-top: 15px;">
                            <a href="https://maps.google.com/?q=Bakmie+Jogja+Zalfa+Cirendeu" target="_blank" style="color: var(--primary-orange); text-decoration: none; font-weight: bold;">Lihat di Google Maps →</a>
                        </div>
                    </div>

                    <div class="location-card">
                        <h4>📍 Cabang Rempoa</h4>
                        <p>Rempoa, Tangerang Selatan (Perbatasan Jaksel)</p>
                        <p style="font-size: 0.9rem; color: #666; margin-top: 5px;">Lokasi strategis dekat Bintaro.</p>
                        <div style="margin-top: 15px;">
                            <a href="https://maps.google.com/?q=Bakmie+Jogja+Zalfa+Rempoa" target="_blank" style="color: var(--primary-orange); text-decoration: none; font-weight: bold;">Lihat di Google Maps →</a>
                        </div>
                    </div>

                    <div class="location-card">
                        <h4>📍 Cabang Bojongsari</h4>
                        <p>Jl. Raya Bojongsari, Depok</p>
                        <p style="font-size: 0.9rem; color: #666; margin-top: 5px;">Super Partner GoFood.</p>
                        <div style="margin-top: 15px;">
                            <a href="https://maps.google.com/?q=Bakmie+Jogja+Zalfa+Bojongsari" target="_blank" style="color: var(--primary-orange); text-decoration: none; font-weight: bold;">Lihat di Google Maps →</a>
                        </div>
                    </div>
                </div>

                <div class="hours-box">
                    <h3>🕒 Jam Operasional</h3>
                    <p style="font-size: 1.1rem; margin-top: 10px;">Buka Setiap Hari</p>
                    <div style="font-size: 3rem; font-weight: 800; color: var(--primary-orange); margin: 10px 0;">16:00</div>
                    <p>Sampai Habis / Tutup</p>
                    
                    <div id="shop-status" class="status-indicator closed">
                        TUTUP SEKARANG
                    </div>
                    <p style="font-size: 0.85rem; opacity: 0.8;">Kami melayani makan malam dengan sepenuh hati.</p>
                </div>
            </div>
        </div>
    </section>

    <footer id="kontak">
        <div class="container">
            <div class="social-links">
                <div class="container">
  <h1>Pelanggan setia</h1>
  <p>Selamat menikmati semoga berkenan dihati</p>
  
  <p>
    Ikuti saya di sosial media: 
    <a href=https://www.instagram.com/bakmiejogjazalfa?igsh=bmRjNmoyMXZhbzJh target="_blank" style="color: purple; text-decoration: none; font-weight: bold;">
      
  📸BakmieJogjaZalfa
    </a>
  </p>

  <hr>

  <p>


    
    Hubungi saya secara langsung: <br>
    <a href="https://wa.me/6285883565428" style="background-color: #25D366; color: white; padding: 2px; text-decoration: none; border-radius: 2px;">
       💬 chat WhatsApp 
    </a>
  </p>

</body>
</html>


            </div>
            <p>© 2024 Bakmie Jogja Zalfa. Seluruh Hak Cipta Dilindungi.</p>
            <p style="margin-top: 10px; font-size: 0.8rem; opacity: 0.6;">Dibuat berdasarkan data menu & lokasi terkini.</p>
        </div>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', function() {
            const now = new Date();
            const hour = now.getHours();
            const statusDiv = document.getElementById('shop-status');
            
            // Logic: Buka jam 16:00 (4 PM) sampai jam 23:00 (11 PM) asumsi
            if (hour >= 16 && hour < 23) {
                statusDiv.textContent = "BUKA SEKARANG";
                statusDiv.classList.remove('closed');
                statusDiv.classList.add('open');
            } else {
                statusDiv.textContent = "TUTUP SEKARANG (Buka jam 16:00)";
                statusDiv.classList.remove('open');
                statusDiv.classList.add('closed');
            }
        });
    </script>
</body>
</html>
