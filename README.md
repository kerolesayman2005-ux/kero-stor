<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>متجر أيمن لمعي - لجميع أنواع الطيور</title>
    <style>
        /* تنسيق عام للموقع */
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; background-color: #f0f2f5; text-align: center; margin: 0; padding: 0; color: #1c1e21; }
        
        /* الصورة الشخصية (أيمن لمعي) */
        .profile-container { margin-top: 40px; }
        .profile-img { 
            width: 150px; 
            height: 150px; 
            border-radius: 50%; 
            border: 6px solid #fff; 
            box-shadow: 0 4px 20px rgba(0,0,0,0.15); 
            object-fit: cover; 
        }

        /* النصوص والترحيب */
        header { padding: 20px; }
        h1 { color: #075e54; font-size: 2.2em; margin-bottom: 5px; }
        .highlight { color: #e44d26; font-weight: bold; }
        .description { font-size: 1.2em; color: #555; max-width: 600px; margin: 0 auto 30px; line-height: 1.6; }

        /* حاوية المنتجات */
        .container { display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; padding: 20px; }

        /* كارت المنتج */
        .product-card { 
            background: #fff; 
            border-radius: 20px; 
            box-shadow: 0 10px 30px rgba(0,0,0,0.1); 
            padding: 20px; 
            width: 280px; 
            transition: 0.3s;
        }
        .product-card:hover { transform: translateY(-10px); }
        .product-card img { width: 100%; border-radius: 15px; height: 180px; object-fit: cover; }
        .product-card h3 { margin: 15px 0; font-size: 1.5em; color: #333; }
        .price { font-size: 1.8em; color: #27ae60; font-weight: bold; margin-bottom: 15px; }

        /* زر الواتساب الاحترافي */
        .buy-btn { 
            background-color: #25d366; 
            color: #fff; 
            text-decoration: none; 
            padding: 12px; 
            border-radius: 12px; 
            display: block; 
            font-weight: bold; 
            font-size: 1.1em;
            transition: 0.3s;
        }
        .buy-btn:hover { background-color: #128c7e; }

        footer { margin: 50px 0; color: #888; border-top: 1px solid #ddd; padding-top: 20px; }
    </style>
</head>
<body>

    <div class="profile-container">
        <img src="WhatsApp Image 2026-01-21 at 7.12.13 PM.jpeg" alt="أيمن لمعي" class="profile-img">
    </div>

    <header>
        <h1>مشروع <span class="highlight">أيمن لمعي</span> لتجارة الطيور</h1>
        <p class="description">
            نحن فخورون بأننا <span class="highlight">أكبر تجارة للبط والفراخ في مصر</span>. 
            خبرة سنوات في اختيار أجود السلالات وتوصيلها لباب بيتك بأفضل الأسعار.
        </p>
    </header>

    <div class="container">
        <div class="product-card">
            <img src="https://images.unsplash.com/photo-1548550023-2bdb3c5beed7?q=80&w=500" alt="فراخ درجة أولى">
            <h3>فراخ بلدي ومزارع</h3>
            <p class="price">10 جنيه</p>
            <a href="https://wa.me/201234567890?text=يا أستاذ أيمن، أريد طلب فراخ" class="buy-btn">اطلب من أيمن الآن ✅</a>
        </div>

        <div class="product-card">
            <img src="https://images.unsplash.com/photo-1555852224-2a3e675cd47e?q=80&w=500" alt="بط مصري">
            <h3>بط مسكوفي ومولار</h3>
            <p class="price">20 جنيه</p>
            <a href="https://wa.me/201234567890?text=يا أستاذ أيمن، أريد طلب بط" class="buy-btn">اطلب البط الآن ✅</a>
        </div>
    </div>

    <footer>
        <p>© 2026 جميع الحقوق محفوظة لـ أيمن لمعي - رائد تجارة الطيور في مصر</p>
    </footer>

</body>
</html>
