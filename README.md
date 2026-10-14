<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Glamby_Tenora | Luxury Makeup Studio</title>
    <link href="https://googleapis.com" rel="stylesheet">
    <style>
        *, *:before, *:after { box-sizing: border-box; }
        body { 
            background-color: #0f0a0d; color: #ffffff; font-family: 'Montserrat', sans-serif; 
            margin: 0; padding: 0; text-align: center; overflow-x: hidden; position: relative;
        }
        #sparkle-canvas {
            position: fixed; top: 0; left: 0; width: 100%; height: 100%; z-index: -1;
            background: radial-gradient(circle at 50% 50%, #29161f 0%, #0f0a0d 100%);
        }
        .shimmer-dust {
            position: absolute; background: linear-gradient(135deg, #ffe4e1 0%, #e6ca9d 50%, #ffb6c1 100%);
            border-radius: 50%; animation: glamFloat 9s ease-in-out infinite; bottom: -60px; opacity: 0.5;
        }
        @keyframes glamFloat {
            0% { transform: translateY(0) scale(0.6) translateX(0); opacity: 0; }
            30% { opacity: 0.7; }
            100% { transform: translateY(-120vh) scale(1.3) translateX(30px); opacity: 0; }
        }
        nav {
            display: flex; justify-content: center; align-items: center; gap: 12px;
            padding: 26px 15px; background: #ffffff; border-bottom: 4px solid #e6ca9d;
            box-shadow: 0 4px 25px rgba(15,10,13,0.3);
        }
        nav h1 { color: #0f0a0d; margin: 0; font-size: 24px; font-weight: 800; letter-spacing: 4px; text-transform: uppercase; }
        .sparkle-icon { font-size: 20px; color: #e6ca9d; }
        header { padding: 80px 20px 50px 20px; }
        header h2 { font-family: 'Playfair Display', serif; font-size: 44px; font-weight: 900; margin: 0 0 25px 0; text-transform: uppercase; line-height: 1.1; }
        header h2 span.pink { color: #ffb6c1; }
        header h2 span.gold { color: #e6ca9d; font-style: italic; text-transform: lowercase; font-weight: 400; }
        header p { color: #ebdce3; max-width: 450px; margin: 0 auto 40px auto; line-height: 1.8; font-size: 16px; }
        .btn-luxe { 
            background: #ffffff; color: #0f0a0d; padding: 18px 45px; text-decoration: none; 
            font-weight: 800; border-radius: 50px; display: inline-block; text-transform: uppercase;
            box-shadow: 0 10px 30px rgba(255,182,193,0.2); border: 2px solid #ffffff; font-size: 13px; letter-spacing: 2px;
        }
        section { padding: 40px 20px; max-width: 450px; margin: 0 auto; }
        .section-headline { font-family: 'Playfair Display', serif; font-size: 32px; font-weight: 900; text-transform: uppercase; margin-bottom: 40px; color: #ffffff; }
        .beauty-card { 
            background: #ffffff; color: #0f0a0d; border-radius: 16px; border-top: 5px solid #ffb6c1;
            padding: 24px; margin-bottom: 22px; display: flex; justify-content: space-between; align-items: center; box-shadow: 0 15px 35px rgba(15,10,13,0.4); text-align: left;
        }
        .beauty-card h4 { margin: 0 0 6px 0; font-size: 19px; font-weight: 800; text-transform: uppercase; }
        .beauty-card p { margin: 0; font-size: 13px; color: #6b5e64; }
        .price-luxury { color: #0f0a0d; font-weight: 800; font-size: 22px; border-bottom: 2px solid #e6ca9d; }
        #galleryGrid { 
            display: grid; grid-template-cols: repeat(3, 1fr); gap: 4px; 
            width: 100%; max-width: 600px; margin: 25px auto 0 auto; padding: 0 4px;
        }
        .gallery-item { width: 100%; aspect-ratio: 1 / 1; overflow: hidden; background-color: #29161f; }
        .gallery-item img { width: 100%; height: 100%; object-fit: cover; display: block; }
        footer { padding: 50px 20px; background: #070406; }
    </style>
</head>
<body>
    <div id="sparkle-canvas"></div>
    <nav>
        <div class="sparkle-icon">✦</div>
        <h1>GLAMBY_TENORA</h1>
        <div class="sparkle-icon">✦</div>
    </nav>
    <header>
        <h2>DEFINE YOUR<br><span class="pink">GLAMOUR.</span> <span class="gold">own it.</span></h2>
        <p>Luxury specialized makeup artistry crafted elegantly to amplify your natural beauty. Flawless bridal sets, striking editorial formats, and signature soft glam updates.</p>
        <a href="tel:+2348135264810" class="btn-luxe">✨ Book Studio Appointment</a>
    </header>
    <section>
        <div class="section-headline">The Menu</div>
        <div class="beauty-card">
            <div>
                <h4>Signature Soft Glam</h4>
                <p>Luminous skin finish, organic shadow definition, and custom lash layout.</p>
            </div>
            <div class="price-luxury">₦15,000</div>
        </div>
        <div class="beauty-card">
            <div>
                <h4>Full Editorial Luxury</h4>
                <p>High-definition mapping, creative color sets, and luxury contour execution.</p>
            </div>
            <div class="price-luxury">₦25,000</div>
        </div>
    </section>
    <section style="max-width: 100%; background: rgba(15, 10, 13, 0.4); padding: 50px 0;">
        <div style="max-width: 450px; margin: 0 auto; padding: 0 20px;">
            <div class="section-headline">The Lookbook</div>
        </div>
        
        <!-- 📸 Perfect Dynamic Row Grid mapped straight to your exact uploaded photos -->
        <div id="galleryGrid">
            <div class="gallery-item"><img src="IMG_8199.jpeg"></div>
            <div class="gallery-item"><img src="IMG_8197.jpeg"></div>
            <div class="gallery-item"><img src="IMG_8189.jpeg"></div>
            <div class="gallery-item"><img src="IMG_8183.jpeg"></div>
            <div class="gallery-item"><img src="IMG_8195.jpeg"></div>
            <div class="gallery-item"><img src="IMG_8184.jpeg"></div>
            <div class="gallery-item"><img src="IMG_8185.png"></div>
        </div>
    </section>
    <footer>
        <p style="font-size: 11px; color: #574850; font-weight: bold; letter-spacing: 1.5px;">© 2026 GLAMBY_TENORA STUDIO. KOSOFE, LAGOS. ALL RIGHTS RESERVED.</p>
    </footer>
    <script>
        const canvas = document.getElementById('sparkle-canvas');
        for (let i = 0; i < 18; i++) {
            const dust = document.createElement('div'); dust.className = 'shimmer-dust';
            const size = Math.random() * 6 + 3;
            dust.style.width = `${size}px`; dust.style.height = `${size}px`;
            dust.style.left = `${Math.random() * 100}%`; dust.style.animationDelay = `${Math.random() * 7}s`;
            canvas.appendChild(dust);
        }
    </script>
</body>
</html>
