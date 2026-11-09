<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>أناقة للمدلات النسائية | الأحذية والحقائب</title>
    <!-- استدعاء خط عربي أنيق -->
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;500;700&display=swap" rel="stylesheet">
    <!-- أيقونات FontAwesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Tajawal', sans-serif;
        }

        body {
            background-color: #fcfbfa;
            color: #2c2c2c;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
            /* خلفية ناعمة دمجت فيها صورة فخمة وشفافة لإعطاء عمق بصري راقي */
            background-image: linear-gradient(rgba(252, 251, 250, 0.92), rgba(252, 251, 250, 0.92)), 
                              url('https://images.unsplash.com/photo-1543163521-1bf539c55dd2?auto=format&fit=crop&w=1200&q=80');
            background-size: cover;
            background-position: center;
        }

        .container {
            width: 100%;
            max-width: 440px;
            background: rgba(255, 255, 255, 0.85);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
            border-radius: 24px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.06);
            overflow: hidden;
            border: 1px solid rgba(212, 175, 55, 0.2);
            text-align: center;
            padding: 30px 20px;
        }

        /* رأس الصفحة والشعار */
        .profile-header {
            margin-bottom: 25px;
        }

        .avatar-container {
            width: 90px;
            height: 90px;
            margin: 0 auto 15px;
            border-radius: 50%;
            overflow: hidden;
            border: 2px solid #d4af37;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }

        .avatar-container img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        h1 {
            font-size: 22px;
            font-weight: 700;
            color: #1a1a1a;
            margin-bottom: 5px;
        }

        p.subtitle {
            font-size: 14px;
            color: #666;
            margin-bottom: 20px;
        }

        /* شريط مصغر يدمج أناقة الحقائب والأحذية كخلفية جمالية متناسقة */
        .mini-banner {
            width: 100%;
            height: 70px;
            border-radius: 12px;
            background-image: url('https://images.unsplash.com/photo-1584917865442-de89df76afd3?auto=format&fit=crop&w=600&q=80');
            background-size: cover;
            background-position: center;
            margin-bottom: 25px;
            box-shadow: inset 0 0 20px rgba(0,0,0,0.2);
        }

        /* قائمة الروابط والأزرار */
        .links-list {
            display: flex;
            flex-direction: column;
            gap: 14px;
        }

        .link-btn {
            display: flex;
            align-items: center;
            justify-content: space-between;
            background: #ffffff;
            color: #2c2c2c;
            text-decoration: none;
            padding: 14px 20px;
            border-radius: 14px;
            font-weight: 500;
            font-size: 15px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.03);
            border: 1px solid rgba(0, 0, 0, 0.04);
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }

        .link-btn i {
            font-size: 18px;
            color: #8c7355;
            transition: transform 0.3s ease;
        }

        .link-btn span {
            flex-grow: 1;
            text-align: center;
        }

        /* تأثيرات اللمس والتحويم للأزرار */
        .link-btn:hover, .link-btn:active {
            background: #1a1a1a;
            color: #ffffff;
            transform: translateY(-2px);
            border-color: #1a1a1a;
        }

        .link-btn:hover i, .link-btn:active i {
            color: #d4af37;
            transform: scale(1.1);
        }

        /* زر مميز للواتساب */
        .link-btn.whatsapp {
            background: #25d366;
            color: white;
            border: none;
        }
        .link-btn.whatsapp i {
            color: white;
        }
        .link-btn.whatsapp:hover {
            background: #1ebe5d;
        }

        /* تذييل الصفحة */
        .footer {
            margin-top: 25px;
            font-size: 12px;
            color: #888;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- معلومات المحل والشعار -->
        <div class="profile-header">
            <div class="avatar-container">
                <!-- صورة حقيقية مصغرة تعبر عن فخامة المنتجات -->
                <img src="https://images.unsplash.com/photo-1595950653106-6c9ebd614d3a?auto=format&fit=crop&w=300&q=80" alt="شعار المحل">
            </div>
            <h1>بوتيك رَوان | Rawand Boutique</h1>
            <p class="subtitle">أرقى تصاميم الأحذية والحقائب النسائية الحصرية</p>
        </div>

        <!-- بانر بصري مصغر مدمج بفن لعرض جمال الحقائب والأحذية -->
        <div class="mini-banner" title="تشكيلة مميزة"></div>

        <!-- الأزرار التفاعلية (Linktree Style) -->
        <div class="links-list">
            <!-- زر الواتساب الرئيسي للطلب -->
            <a href="https://wa.me/966500000000" target="_blank" class="link-btn whatsapp">
                <i class="fa-brands fa-whatsapp"></i>
                <span>طلب واستفسار عبر الواتساب</span>
                <i class="fa-solid fa-chevron-left" style="font-size: 11px;"></i>
            </a>

            <!-- زر كتالوج المنتجات -->
            <a href="#" class="link-btn">
                <i class="fa-solid fa-bag-shopping"></i>
                <span>تصفح كتالوج الحقائب والأحذية</span>
                <i class="fa-solid fa-chevron-left" style="font-size: 11px;"></i>
            </a>

            <!-- زر إنستغرام -->
            <a href="#" target="_blank" class="link-btn">
                <i class="fa-brands fa-instagram"></i>
                <span>تابعنا على إنستغرام</span>
                <i class="fa-solid fa-chevron-left" style="font-size: 11px;"></i>
            </a>

            <!-- زر موقع المحل على الخريطة -->
            <a href="#" target="_blank" class="link-btn">
                <i class="fa-solid fa-location-dot"></i>
                <span>موقعنا على الخريطة (فرع الرياض)</span>
                <i class="fa-solid fa-chevron-left" style="font-size: 11px;"></i>
            </a>
        </div>

        <!-- حقوق النشر -->
        <div class="footer">
            جميع الحقوق محفوظة &copy; 2026
        </div>
    </div>

</body>
</html>
