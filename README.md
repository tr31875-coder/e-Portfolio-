<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>E-Portfolio | ชิติพัทธ์</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; scroll-behavior: smooth; }
    body {
      font-family: Arial, sans-serif;
      background: #081120;
      color: #f5f7fa;
      line-height: 1.6;
    }
    header {
      background: #101d35;
      position: sticky;
      top: 0;
      z-index: 10;
      box-shadow: 0 2px 10px rgba(0,0,0,0.2);
    }
    nav {
      max-width: 1200px;
      margin: 0 auto;
      padding: 18px 24px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      gap: 12px;
    }
    nav h2 {
      color: #00aaff;
      font-size: 1.4rem;
      letter-spacing: 1px;
    }
    nav .menu {
      display: flex;
      flex-wrap: wrap;
      gap: 16px;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: 600;
    }
    nav a:hover { color: #00aaff; }

    section {
      max-width: 1200px;
      margin: 0 auto;
      padding: 80px 24px;
      text-align: center;
    }

    .hero {
      min-height: 500px;
      display: flex;
      justify-content: center;
      align-items: center;
      background: linear-gradient(135deg, #071326, #123d70);
      padding: 50px 24px;
    }
    .hero-content {
      max-width: 800px;
    }
    .hero p {
      font-size: 1.1rem;
      letter-spacing: 0.08em;
      color: #cfe8ff;
    }
    .hero h1 {
      margin: 18px 0;
      font-size: clamp(2.2rem, 4vw, 3.8rem);
      color: #00aaff;
    }
    .hero h2 {
      font-size: clamp(1.2rem, 2vw, 2rem);
      margin-bottom: 8px;
    }
    .btn {
      display: inline-block;
      margin-top: 26px;
      padding: 12px 24px;
      background: #008cff;
      color: white;
      border-radius: 10px;
      text-decoration: none;
      font-weight: 700;
      transition: 0.2s ease;
    }
    .btn:hover { background: #1ea8ff; }

    h2 {
      color: #00aaff;
      font-size: clamp(1.8rem, 2.5vw, 2.6rem);
      margin-bottom: 28px;
    }

    .card {
      background: #14243d;
      border: 1px solid #1763a5;
      border-radius: 18px;
      max-width: 780px;
      margin: 0 auto;
      padding: 30px;
      text-align: left;
      box-shadow: 0 6px 18px rgba(0,0,0,0.15);
    }
    .card h3 {
      color: #00ccff;
      margin-bottom: 10px;
      font-size: 1.4rem;
    }
    .card p {
      margin-bottom: 8px;
      color: #eef5ff;
    }

    footer {
      background: #101d35;
      text-align: center;
      padding: 22px 16px;
      color: #8ea8cc;
    }

    @media (max-width: 600px) {
      nav {
        justify-content: center;
        text-align: center;
      }
      .menu {
        justify-content: center;
      }
      section {
        padding: 60px 18px;
      }
      .card {
        padding: 22px 18px;
      }
    }
  </style>
</head>
<body>
  <header>
    <nav>
      <h2>MY PORTFOLIO</h2>
      <div class="menu">
        <a href="#home">หน้าแรก</a>
        <a href="#about">ประวัติ</a>
        <a href="#skills">ทักษะ</a>
        <a href="#projects">ผลงาน</a>
        <a href="#contact">ติดต่อ</a>
      </div>
    </nav>
  </header>

  <section class="hero" id="home">
    <div class="hero-content">
      <p>WELCOME TO MY PORTFOLIO</p>
      <h1>นายชิติพัทธ์ พรมสุภา</h1>
      <h2>นักเรียนชั้นมัธยมศึกษาปีที่ 6/13</h2>
      <p>เลขที่ 4</p>
      <a href="#about" class="btn">รู้จักฉันเพิ่มเติม</a>
    </div>
  </section>

  <section id="about">
    <h2>ประวัติส่วนตัว</h2>
    <div class="card">
      <h3>ข้อมูลส่วนตัว</h3>
      <p>ชื่อ : นายชิติพัทธ์ พรมสุภา</p>
      <p>ชั้น : ม.6/13</p>
      <p>เลขที่ : 4</p>
      <p>โรงเรียน : (ใส่ชื่อโรงเรียน)</p>
      <p>ความสนใจ : เทคโนโลยีและคอมพิวเตอร์</p>
    </div>
  </section>

  <section id="skills">
    <h2>ทักษะความสามารถ</h2>
    <div class="card">
      <h3>Programming</h3>
      <p>การเขียนโปรแกรมคอมพิวเตอร์</p>
      <h3>Technology</h3>
      <p>เทคโนโลยี IoT และเซนเซอร์</p>
      <h3>Problem Solving</h3>
      <p>การคิดวิเคราะห์และแก้ไขปัญหา</p>
    </div>
  </section>

  <section id="projects">
    <h2>ผลงานของฉัน</h2>
    <div class="card">
      <h3>ระบบตรวจสอบสภาพอากาศและ PM2.5</h3>
      <p>
        เป็นโครงงานที่นำเทคโนโลยี IoT และเซนเซอร์มาใช้ตรวจสอบสภาพอากาศ
        เช่น อุณหภูมิ ความชื้น และค่าฝุ่น PM2.5
      </p>
      <p>ประโยชน์: ช่วยติดตามคุณภาพอากาศ</p>
    </div>
  </section>

  <section id="contact">
    <h2>ติดต่อ</h2>
    <div class="card">
      <p>ชื่อ: ชิติพัทธ์ พรมสุภา</p>
      <p>ชั้น: ม.6/13 เลขที่ 4</p>
      <p>GitHub: เพิ่มลิงก์บัญชีของตนเอง</p>
    </div>
  </section>

  <footer>
    <p id="copyright"></p>
  </footer>

  <script>
    document.getElementById("copyright").textContent =
      "© " + new Date().getFullYear() + " E-Portfolio | ชิติพัทธ์ พรมสุภา";
  </script>
</body>
</html>
