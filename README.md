<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cafe Toudert - مقهى تودرت</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body { background-color: #f8f9fa; font-family: 'Arial', sans-serif; }
        .hero { background: linear-gradient(to right, #8B4513, #D2691E); color: white; padding: 100px 0; text-align: center; }
        .section-title { color: #8B4513; margin-bottom: 30px; }
        .card { border: none; box-shadow: 0 4px 8px rgba(0,0,0,0.1); }
        footer { background-color: #343a40; color: white; padding: 20px 0; }
    </style>
</head>
<body>
    <!-- شريط التنقل -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Cafe Toudert</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#about">عن المقهى</a></li>
                    <li class="nav-item"><a class="nav-link" href="#menu">القائمة</a></li>
                    <li class="nav-item"><a class="nav-link" href="#gallery">المعرض</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">اتصل بنا</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- قسم البطل (Hero) -->
    <section class="hero">
        <div class="container">
            <h1>مرحبا بكم في Cafe Toudert</h1>
            <p>مقهى تودرت - أفضل مكان للقهوة الطازجة والاسترخاء</p>
            <img src="https://via.placeholder.com/800x400?text=Cafe+Toudert+Exterior" alt="صورة خارجية للمقهى" class="img-fluid mt-3">
        </div>
    </section>

    <!-- عن المقهى -->
    <section id="about" class="py-5">
        <div class="container">
            <h2 class="section-title text-center">عن المقهى</h2>
            <div class="row">
                <div class="col-md-6">
                    <p>نحن نقدم قهوة طازجة، مشروبات ساخنة وباردة، وأجواء مريحة للجميع. زورونا لتجربة فريدة!</p>
                </div>
                <div class="col-md-6">
                    <img src="https://via.placeholder.com/500x300?text=Cafe+Interior" alt="صورة داخلية" class="img-fluid">
                </div>
            </div>
        </div>
    </section>

    <!-- القائمة -->
    <section id="menu" class="py-5 bg-light">
        <div class="container">
            <h2 class="section-title text-center">قائمة القهوة</h2>
            <div class="row">
                <div class="col-md-3">
                    <div class="card text-center">
                        <img src="https://via.placeholder.com/200x150?text=Arabic+Coffee" class="card-img-top" alt="قهوة عربية">
                        <div class="card-body">
                            <h5>قهوة عربية</h5>
                            <p>5 دراهم</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card text-center">
                        <img src="https://via.placeholder.com/200x150?text=Latte" class="card-img-top" alt="لاتيه">
                        <div class="card-body">
                            <h5>لاتيه</h5>
                            <p>8 دراهم</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card text-center">
                        <img src="https://via.placeholder.com/200x150?text=Green+Tea" class="card-img-top" alt="شاي أخضر">
                        <div class="card-body">
                            <h5>شاي أخضر</h5>
                            <p>6 دراهم</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card text-center">
                        <img src="https://via.placeholder.com/200x150?text=Orange+Juice" class="card-img-top" alt="عصير برتقال">
                        <div class="card-body">
                            <h5>عصير برتقال</h5>
                            <p>7 دراهم</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- معرض الصور -->
    <section id="gallery" class="py-5">
        <div class="container">
            <h2 class="section-title text-center">معرض الصور</h2>
            <div class="row">
                <div class="col-md-4"><img src="https://via.placeholder.com/300x200?text=Cafe+Photo+1" class="img-fluid mb-3" alt="صورة 1"></div>
                <div class="col-md-4"><img src="https://via.placeholder.com/300x200?text=Cafe+Photo+2" class="img-fluid mb-3" alt="صورة 2"></div>
                <div class="col-md-4"><img src="https://via.placeholder.com/300x200?text=Cafe+Photo+3" class="img-fluid mb-3" alt="صورة 3"></div>
            </div>
        </div>
    </section>

    <!-- اتصل بنا -->
    <section id="contact" class="py-5 bg-light">
        <div class="container">
            <h2 class="section-title text-center">اتصل بنا</h2>
            <div class="row">
                <div class="col-md-6">
                    <p><strong>العنوان:</strong> [أدخل عنوانك هنا]</p>
                    <p><strong>الهاتف:</strong> [أدخل رقم هاتفك هنا]</p>
                    <p><strong>البريد الإلكتروني:</strong> info@cafetoudert.com</p>
                </div>
                <div class="col-md-6">
                    <img src="https://via.placeholder.com/500x300?text=Location+Map" alt="خريطة الموقع" class="img-fluid">
                </div>
            </div>
        </div>
    </section>

    <!-- تذييل -->
    <footer class="text-center">
        <div class="container">
            <p>&copy; 2023 Cafe Toudert. جميع الحقوق محفوظة.</p>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
