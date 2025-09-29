<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Taxi Smart 24/7</title>
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
    header h1 { color: var(--main-color); font-weight: 700; font-size: 24px; }
    nav a {
      margin: 0 15px; text-decoration: none; color: var(--dark);
      font-weight: 500; transition: 0.3s;
    }
    nav a:hover { color: var(--main-color); }
    .hero {
      height: 100vh;
      background: url('https://images.unsplash.com/photo-1502877338535-766e1452684a') center/cover no-repeat;
      display: flex; align-items: center; justify-content: center;
      text-align: center; color: white; position: relative;
    }
    .hero::after {
      content: ""; position: absolute; top: 0; left: 0; right: 0; bottom: 0;
      background: rgba(0,0,0,0.55);
    }
    .hero-content {
      position: relative; z-index: 1; max-width: 700px;
    }
    .hero-content h2 { font-size: 52px; margin-bottom: 20px; }
    .hero-content p { font-size: 20px; margin-bottom: 30px; }
    .btn {
      display: inline-block; padding: 12px 25px; border-radius: 8px;
      background: var(--main-color); color: var(--dark); font-weight: bold;
      text-decoration: none; transition: 0.3s;
    }
    .btn:hover { background: #eab308; }
    .section { padding: 100px 50px; text-align: center; }
    .section h2 { font-size: 36px; margin-bottom: 20px; color: var(--dark); }
    .section p { max-width: 700px; margin: 0 auto 40px; color: #555; }
    .features {
      display: flex; flex-wrap: wrap; justify-content: center; gap: 30px;
    }
    .feature {
      background: var(--gray); padding: 30px; border-radius: 12px;
      flex: 1 1 280px; transition: transform 0.3s;
    }
    .feature:hover { transform: translateY(-8px); }
    .feature h3 { margin-bottom: 10px; color: var(--dark); }

    /* Form */
    .form-box {
      max-width: 600px; margin: 0 auto; background: var(--gray);
      padding: 40px; border-radius: 12px; text-align: left;
    }
    .form-box label { font-weight: 600; display: block; margin-bottom: 6px; }
    .form-box input, .form-box select {
      width: 100%; padding: 12px; margin-bottom: 20px;
      border: 1px solid #ccc; border-radius: 8px; font-size: 16px;
    }
    .form-box button {
      width: 100%; padding: 14px;
      background: var(--main-color); border: none; border-radius: 8px;
      font-size: 18px; font-weight: bold; color: var(--dark);
      cursor: pointer; transition: 0.3s;
    }
    .form-box button:hover { background: #eab308; }
    footer {
      background: var(--dark); color: var(--light);
      text-align: center; padding: 30px 20px;
    }
    footer a { color: var(--main-color); text-decoration: none; }
  </style>
</head>
<body>
  <header>
    <h1>🚖 Taxi Smart</h1>
    <nav>
      <a href="#about">Giới thiệu</a>
      <a href="#services">Dịch vụ</a>
      <a href="#booking">Đặt xe</a>
      <a href="#contact">Liên hệ</a>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-content">
      <h2>Taxi hiện đại - Đặt xe chỉ trong 1 phút</h2>
      <p>An toàn • Nhanh chóng • Giá tốt</p>
      <a href="#booking" class="btn">📞 Hotline: 0833 355 063</a>
    </div>
  </section>

  <section id="about" class="section">
    <h2>Về chúng tôi</h2>
    <p>Taxi Smart 24/7 mang đến trải nghiệm đặt xe thông minh,
      tích hợp công nghệ hiện đại, dễ dàng sử dụng chỉ với vài thao tác.
      Chúng tôi cam kết phục vụ an toàn, nhanh chóng và minh bạch về giá.</p>
  </section>

  <section id="services" class="section">
    <h2>Dịch vụ nổi bật</h2>
    <div class="features">
      <div class="feature">
        <h3>🚖 Taxi Thành Phố</h3>
        <p>Phù hợp di chuyển hằng ngày, đặt xe nhanh trong vài giây.</p>
      </div>
      <div class="feature">
        <h3>🛫 Taxi Sân Bay</h3>
        <p>Đưa đón sân bay đúng giờ, tiện lợi và giá minh bạch.</p>
      </div>
      <div class="feature">
        <h3>🌙 Taxi Đêm</h3>
        <p>Hoạt động 24/7, an toàn tuyệt đối, luôn sẵn sàng phục vụ.</p>
      </div>
    </div>
  </section>

  <section id="booking" class="section">
    <h2>Đặt xe trực tuyến</h2>
    <p>Điền thông tin dưới đây để đặt xe nhanh chóng. Hoặc gọi ngay 📞 <b>0833 355 063</b></p>
    <div class="form-box">
      <form>
        <label for="pickup">Điểm đón</label>
        <input type="text" id="pickup" name="pickup" placeholder="Nhập địa chỉ điểm đón" required>

        <label for="dropoff">Điểm đến</label>
        <input type="text" id="dropoff" name="dropoff" placeholder="Nhập địa chỉ điểm đến" required>

        <label for="time">Thời gian đón</label>
        <input type="datetime-local" id="time" name="time" required>

        <label for="car">Loại xe</label>
        <select id="car" name="car">
          <option>4 chỗ</option>
          <option>7 chỗ</option>
          <option>16 chỗ</option>
        </select>

        <button type="submit">🚖 Đặt xe ngay</button>
      </form>
    </div>
  </section>

  <section id="contact" class="section">
    <h2>Liên hệ</h2>
    <p>📍 Địa chỉ: Alo là có xe</p>
    <p>📞 Hotline: <b>0833 355 063</b></p>
    <p>📧 Email: tuyetnhan317@gmail.com</p>
  </section>

  <footer>
    <p>© 2025 Taxi Smart. Thiết kế bởi <a href="#">Piino</a>.</p>
  </footer>
</body>
</html>
