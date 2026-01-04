# Yahya-Sancar-tekstil-A.-
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yahya Sancar Tekstil A.Ş. | Premium Collection</title>
    <style>
        :root {
            --ana-mavi: #007bff;
            --koyu-mavi: #001a4d;
            --acik-mavi: #e6f0ff;
            --beyaz: #ffffff;
        }

        body {
            margin: 0;
            font-family: 'Poppins', sans-serif;
            background-color: var(--beyaz);
            color: var(--koyu-mavi);
            overflow-x: hidden;
        }

        /* Arka Plan: Logodaki çizgiler ve renk karışımı */
        .bg-pattern {
            position: fixed;
            top: 0; left: 0; width: 100%; height: 100%;
            z-index: -1;
            background: linear-gradient(135deg, var(--beyaz) 0%, var(--acik-mavi) 50%, #d1e3ff 100%);
            opacity: 0.6;
        }
        
        .logo-lines {
            position: absolute;
            width: 300px; height: 300px;
            border-right: 50px solid var(--ana-mavi);
            transform: rotate(45deg);
            top: -100px; right: -50px;
            opacity: 0.1;
        }

        /* Navigasyon */
        nav {
            background: rgba(255, 255, 255, 0.95);
            padding: 20px 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 15px rgba(0,0,0,0.1);
        }

        .logo-text {
            font-size: 24px;
            font-weight: 800;
            color: var(--koyu-mavi);
            letter-spacing: 1px;
        }

        /* Hero Bölümü */
        .hero {
            height: 70vh;
            display: flex;
            align-items: center;
            justify-content: center;
            background: linear-gradient(rgba(0,26,77,0.6), rgba(0,26,77,0.6)), 
                        url('https://images.unsplash.com/photo-1441984904996-e0b6ba687e04?auto=format&fit=crop&w=1500&q=80');
            background-size: cover;
            background-position: center;
            color: white;
            text-align: center;
        }

        /* Koleksiyonlar */
        .section-title {
            text-align: center;
            font-size: 32px;
            margin: 50px 0;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        .category-container {
            padding: 0 5%;
            margin-bottom: 80px;
        }

        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }

        .product-card {
            background: white;
            border-radius: 12px;
            overflow: hidden;
            transition: 0.4s;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
            border: 1px solid #eee;
        }

        .product-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0,0,0,0.15);
        }

        .product-card img {
            width: 100%;
            height: 300px;
            object-fit: cover;
        }

        .product-info {
            padding: 15px;
            text-align: center;
        }

        /* İletişim */
        .contact-box {
            background: var(--koyu-mavi);
            color: white;
            padding: 80px 5%;
            text-align: center;
        }

        .contact-btn {
            display: inline-block;
            padding: 18px 40px;
            background: var(--ana-mavi);
            color: white;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            font-size: 18px;
            transition: 0.3s;
            margin-top: 25px;
        }

        .contact-btn:hover {
            background: var(--beyaz);
            color: var(--ana-mavi);
        }

        footer {
            padding: 30px;
            text-align: center;
            background: #000b21;
            color: rgba(255,255,255,0.6);
            font-size: 14px;
        }
    </style>
</head>
<body>

<div class="bg-pattern"></div>
<div class="logo-lines"></div>

<nav>
    <div class="logo-text">YAHYA SANCAR TEKSTİL A.Ş.</div>
    <div style="font-weight: 500;">Kadın | Erkek | Çocuk | İletişim</div>
</nav>

<div class="hero">
    <div>
        <h1 style="font-size: 50px;">GELECEĞİN MODASI</h1>
        <p style="font-size: 20px;">Yahya Sancar Güvencesiyle Premium Tekstil Çözümleri</p>
    </div>
</div>

<div class="category-container">
    <h2 class="section-title">Kadın Giyim Koleksiyonu</h2>
    <div class="product-grid">
        <div class="product-card"><img src="https://images.unsplash.com/photo-1539109136881-3be0616acf4b?w=400" alt="K1"> <div class="product-info">Elbise</div></div>
        <div class="product-card"><img src="https://images.unsplash.com/photo-1564485377539-4af72d1f6a2f?w=400" alt="K2"> <div class="product-info">Ceket</div></div>
        <div class="product-card"><img src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?w=400" alt="K3"> <div class="product-info">Tasarım</div></div>
        <div class="product-card"><img src="https://images.unsplash.com/photo-1515886657613-9f3515b0c78f?w=400" alt="K4"> <div class="product-info">Trend</div></div>
        <div class="product-card"><img src="https://images.unsplash.com/photo-1485230895905-ec17ba36b5bc?w=400" alt="K5"> <div class="product-info">Abiye</div></div>
    </div>
</div>

<div class="category-container">
    <h2 class="section-title" style="color: var(--ana-mavi);">Erkek Giyim Koleksiyonu</h2>
    <div class="product-grid">
        <div class="product-card"><img src="https://images.unsplash.com/photo-1488161628813-04466f872be2?w=400" alt="E1"> <div class="product-info">Gömlek</div></div>
        <div class="product-card"><img src="https://images.unsplash.com/photo-1519085360753-af0119f7cbe7?w=400" alt="E2"> <div class="product-info">Takım Elbise</div></div>
        <div class="product-card"><img src="https://images.unsplash.com/photo-1492562080023-ab3db95bfbce?w=400" alt="E3"> <div class="product-info">Casual</div></div>
        <div class="product-card"><img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?w=400" alt="E4"> <div class="product-info">Kaban</div></div>
        <div class="product-card"><img src="https://images.unsplash.com/photo-1617137984095-74e4e5e3613f?w=400" alt="E5"> <div class="product-info">Spor Giyim</div></div>
    </div>
</div>

<div class="category-container">
    <h2 class="section-title">Çocuk Giyim Koleksiyonu</h2>
    <div class="product-grid">
        <div class="product-card"><img src="https://images.unsplash.com/photo-1519234110483-e5df3a233367?w=400" alt="C1"> <div class="product-info">Bebek</div></div>
        <div class="product-card"><img src="https://images.unsplash.com/photo-1503919545889-aef636e10ad4?w=400" alt="C2"> <div class="product-info">Kız Çocuk</div></div>
        <div class="product-card"><img src="https://images.unsplash.com/photo-1519457431-7571f55b814b?w=400" alt="C3"> <div class="product-info">Erkek Çocuk</div></div>
        <div class="product-card"><img src="https://images.unsplash.com/photo-1537633552985-df8429e8048b?w=400" alt="C4"> <div class="product-info">Yeni Sezon</div></div>
        <div class="product-card"><img src="https://images.unsplash.com/photo-1604467731651-bb38b1845124?w=400" alt="C5"> <div class="product-info">Pijama</div></div>
    </div>
</div>

<div class="contact-box">
    <h2>Profesyonel İş Ortaklığı İçin</h2>
    <p>Yahya Sancar Tekstil A.Ş. dünya standartlarında üretim kapasitesine sahiptir.</p>
    <a href="mailto:yahyasancarhto@gmail.com" class="contact-btn">Bize E-posta Gönder</a>
    <p style="margin-top: 20px; font-size: 14px; opacity: 0.8;">yahyasancarhto@gmail.com</p>
</div>

<footer>
    &copy; 2026 Yahya Sancar Tekstil A.Ş. | Kalitenin ve Güvenin Tek Adresi.
</footer>

</body>
</html>
