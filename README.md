<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Taxi Đà Lạt 24/7</title>
  <meta name="description" content="Dịch vụ taxi nhanh chóng, an toàn và tiện lợi 24/7. Đặt xe ngay qua số 0833 355 063 hoặc điền form để được phục vụ.">

  <!-- Import font Poppins -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">

  <style>
    :root {
      --main-color: #facc15; /* vàng */
      --dark: #111;
      --light: #fff;
      --gray: #f3f4f6;
    }
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: "Poppins", sans-serif;
      color: var(--dark);
      background: var(--light);
      line-height: 1.6;
      padding-top: 80px; /* tránh header che nội dung */
    }

    header {
      position: fixed; top: 0; left: 0;
      width: 100%;
      background: rgba(255,255,255,0.9);
      backdrop-filter: blur(10px);
      display: flex; justify-content: space-between; align-items: center;
      padding: 15px 50px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
      z-index: 1000;
    }
    header h1 {
      color: var(--main-color);
      font-weight: 700; font-size: 24px;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: var(--dark);
      font-weight: 500;
      transition: 0.3s;
    }
    nav a:hover { color: var(--main-color); }

    .hero {
      height: 100vh;
      background: url('https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=1920&q=80') center/cover no-repeat;
      display: flex; align-items: center; justify-content: center;
      text-align: center; color: white;
      position: relative;
    }
    .hero::after {
      content: ""; position: absolute; top: 0; left: 0; right: 0; bottom: 0;
      background: rgba(0,0,0,0.55);
    }
    .hero-content {
      position: relative; z-index: 1;
      max-width: 700px;
    }
    .hero-content h2 { font-size: 52px; margin-bottom: 20px; }
    .hero-content p { font-size: 20px; margin-bottom: 30px; }

    .btn {
      display: inline-block;
      padding: 12px 25px;
      border-radius: 8px;
      background: var(--main-color);
      color: var(--dark);
      font-weight: bold;
      text-decoration: none;
      transition: 0.3s;
    }
    .btn:hover { background: #eab308; }

    .section { padding: 100px 50px; text-align: center; }
    .section h2 { font-size: 36px; margin-bottom: 20px; color: var(--dark); }
    .section p { max-width: 700px; margin: 0 auto 40px; color: #555; }

    .features {
      display: flex; flex-wrap: wrap; justify-content: center; gap: 30px;
    }
    .feature {
      background: var(--gray);
      padding: 30px;
      border-radius: 12px;
      flex: 1 1 280px;
      transition: transform 0.3s;
    }
    .feature:hover { transform: translateY(-8px); }

    footer {
      background: var(--dark);
      color: var(--light);
      text-align: center;
      padding: 30px 20px;
    }
    footer a { color: var(--main-color); text-decoration: none; }

    /* Form đặt xe */
    form {
      max-width: 500px;
      margin: 0 auto;
      text-align: left;
    }
    form input, form textarea {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 8px;
      font-family: inherit;
    }
    form button {
      background: var(--main-color);
      border: none;
      padding: 12px 25px;
      border-radius: 8px;
      font-weight: bold;
      cursor: pointer;
    }
    form button:hover { background: #eab308; }

    /* Responsive */
    @media (max-width: 768px) {
      header { padding: 12px 20px; }
      .hero-content h2 { font-size: 32px; }
      .hero-content p { font-size: 16px; }
      .section { padding: 60px 20px; }
      nav a { margin: 0 8px; font-size: 14px; }
    }
  </style>
</head>
<body>
  <header>
    <h1>🚖 Taxi Đà Lạt Giá Rẻ</h1>
    <nav aria-label="Main navigation">
      <a href="#about">Giới thiệu</a>
      <a href="#services">Dịch vụ</a>
      <a href="#contact">Liên hệ</a>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-content">
      <h2>Dịch vụ Taxi Đà Lạt 24/7</h2>
      <p>Đặt taxi nhanh chóng, an toàn, giá cả hợp lý. Hotline <a href="tel:0833355063" style="color:yellow;">0833 355 063</a></p>
      <a class="btn" href="#contact">📞 Đặt xe ngay</a>
    </div>
  </section>

  <section id="about" class="section">
    <h2>Về Chúng Tôi</h2>
    <p>Dịch vụ Taxi Đà Lạt cung cấp dịch vụ di chuyển nhanh chóng, an toàn, tận tâm với khách hàng. Chúng tôi luôn sẵn sàng phục vụ bạn mọi lúc mọi nơi.</p>
  </section>

  <section id="services" class="section">
    <h2>Dịch Vụ</h2>
    <div class="features">
      <div class="feature">🚕 Đưa đón sân bay</div>
      <div class="feature">🚖 Taxi nội thành</div>
      <div class="feature">🕒 Phục vụ 24/7</div>
      <div class="feature">💳 Thanh toán tiện lợi</div>
    </div>
  </section>

  <section id="contact" class="section">
    <h2>Liên Hệ & Đặt Xe</h2>
    <p>Bạn có thể gọi ngay qua số <a href="tel:0833355063">0833 355 063</a> hoặc điền form dưới đây:</p>

    <!-- Formspree form -->
    <form action="https://formspree.io/f/mwpegrjz" method="POST">
      <input type="text" name="name" placeholder="Họ tên của bạn" required>
      <input type="tel" name="phone" placeholder="Số điện thoại" required>
      <textarea name="message" rows="4" placeholder="Địa điểm đón/trả, thời gian" required></textarea>
      <button type="submit">Gửi yêu cầu</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Taxi Đà Lạt 24/7. Mọi quyền được bảo lưu. | Hotline <a href="tel:0833355063">0833 355 063</a></p>
  </footer>
</body>
</html>
