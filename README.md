<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>e-Portfolio | [ใส่ชื่อ-นามสกุลของคุณ]</title>
    <style>
        /* การตกแต่งพื้นฐาน */
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; margin: 0; padding: 0; line-height: 1.6; color: #333; background-color: #f4f7f6; }
        html { scroll-behavior: smooth; }
        
        /* แถบเมนูนำทาง */
        nav { background-color: #2c3e50; padding: 15px 0; position: sticky; top: 0; z-index: 1000; text-align: center; }
        nav a { color: white; text-decoration: none; margin: 0 15px; font-weight: bold; font-size: 16px; }
        nav a:hover { color: #3498db; }

        /* ส่วนหัว (Header) */
        header { background: linear-gradient(135deg, #3498db, #2c3e50); color: white; text-align: center; padding: 60px 20px; }
        .profile-img { width: 150px; height: 150px; border-radius: 50%; object-fit: cover; border: 4px solid white; margin-bottom: 15px; }
        
        /* จัดหน้าเนื้อหา */
        .container { max-width: 900px; margin: 20px auto; padding: 20px; background: white; border-radius: 8px; box-shadow: 0 2px 10px rgba(0,0,0,0.1); }
        h2 { color: #2c3e50; border-bottom: 2px solid #3498db; padding-bottom: 5px; }
        
        /* การ์ดแสดงผลงาน */
        .project-card { border: 1px solid #ddd; padding: 20px; border-radius: 8px; margin-top: 15px; background: #fafafa; }
        .btn { display: inline-block; background: #3498db; color: white; padding: 10px 20px; text-decoration: none; border-radius: 5px; margin-top: 10px; }
        .btn:hover { background: #2980b9; }

        /* ส่วนท้าย (Footer) */
        footer { text-align: center; padding: 20px; background: #2c3e50; color: white; margin-top: 40px; }
    </style>
</head>
<body>

    <!-- 1. เมนูนำทาง -->
    <nav>
        <a href="#about">ประวัติส่วนตัว</a>
        <a href="#skills">ทักษะ</a>
        <a href="#projects">ผลงานโค้ด</a>
        <a href="#contact">ติดต่อ</a>
    </nav>

    <!-- 2. ส่วนแนะนำตัวหลัก -->
    <header>
        <!-- เปลี่ยนลิงก์รูปภาพตรง src เป็นรูปของคุณ หรืออัปโหลดรูปชื่อ profile.jpg ไว้ในโฟลเดอร์เดียวกัน -->
        <img src="https://via.placeholder.com/150" alt="รูปโปรไฟล์" class="profile-img">
        <h1>สวัสดีครับ/ค่ะ ผมชื่อ [ใส่ชื่อ-นามสกุลของคุณ]</h1>
        <p>นักเรียนชั้นมัธยมศึกษาปีที่ [X] | โรงเรียน [ใส่ชื่อโรงเรียนของคุณ]</p>
    </header>

    <!-- 3. ประวัติส่วนตัว -->
    <div id="about" class="container">
        <h2>ประวัติส่วนตัว (About Me)</h2>
        <p>เขียนแนะนำตัวเองสั้นๆ เช่น ความสนใจด้านเทคโนโลยี การเขียนโปรแกรม เป้าหมายในอนาคต หรือคติประจำใจของคุณ</p>
    </div>

    <!-- 4. ทักษะความสามารถ -->
    <div id="skills" class="container">
        <h2>ทักษะด้านคอมพิวเตอร์ (Skills)</h2>
        <ul>
            <li>การเขียนโปรแกรมเบื้องต้น: Python, HTML, CSS</li>
            <li>การใช้เครื่องมือ AI ช่วยในการพัฒนาซอฟต์แวร์และออกแบบ</li>
            <li>การใช้งาน Git และ GitHub</li>
        </ul>
    </div>

    <!-- 5. ผลงานโค้ด (ตามโจทย์: เชื่อมโยงผลงานโค้ด 1 ชิ้น) -->
    <div id="projects" class="container">
        <h2>ผลงานการเขียนโค้ด (Coding Project)</h2>
        <div class="project-card">
            <h3>ชื่อผลงาน: [เช่น โปรแกรมคำนวณเกรดเฉลี่ย / เกมทายตัวเลข]</h3>
            <p><strong>รายละเอียด:</strong> อธิบายสั้นๆ ว่าโค้ดนี้ทำงานอย่างไร และใช้ภาษาอะไรในการเขียน</p>
            <!-- เปลี่ยน # เป็นลิงก์ GitHub Repository หรือ Google Colab / Replit ของผลงานโค้ดชิ้นนั้น -->
            <a href="https://github.com/username/project-name" target="_blank" class="btn">ดูซอร์สโค้ด (Source Code)</a>
        </div>
    </div>

    <!-- 6. ช่องทางติดต่อ -->
    <div id="contact" class="container">
        <h2>ช่องทางติดต่อ (Contact)</h2>
        <p>อีเมล: your.email@example.com</p>
        <p>GitHub: <a href="https://github.com/yourusername" target="_blank">github.com/yourusername</a></p>
    </div>

    <footer>
        <p>© 2026 จัดทำโดย [ชื่อ-นามสกุลของคุณ] - สร้างด้วย HTML/CSS และเผยแพร่บน GitHub Pages</p>
    </footer>

</body>
</html>
