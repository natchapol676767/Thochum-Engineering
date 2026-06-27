# Thochum-Engineering
HOME
<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ABC Construction</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: Arial, sans-serif;
}

body{
    line-height:1.6;
}

header{
    background:#222;
    color:#fff;
    padding:20px;
}

nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    font-size:24px;
    font-weight:bold;
}

nav ul{
    list-style:none;
    display:flex;
    gap:20px;
}

nav a{
    color:#fff;
    text-decoration:none;
}

.hero{
    background:url('https://images.unsplash.com/photo-1503387762-592deb58ef4e?auto=format&fit=crop&w=1400&q=80')
    center/cover;
    height:500px;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    color:white;
}

.hero-content{
    background:rgba(0,0,0,0.6);
    padding:30px;
    border-radius:10px;
}

.btn{
    display:inline-block;
    margin-top:15px;
    padding:12px 25px;
    background:#f39c12;
    color:white;
    text-decoration:none;
    border-radius:5px;
}

section{
    padding:60px 10%;
}

h2{
    text-align:center;
    margin-bottom:30px;
}

.services{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.card{
    background:#f4f4f4;
    padding:30px;
    border-radius:10px;
    text-align:center;
    box-shadow:0 2px 10px rgba(0,0,0,0.1);
}

footer{
    background:#222;
    color:white;
    text-align:center;
    padding:20px;
}
</style>
</head>
<body>

<header>
    <nav>
        <div class="logo">ABC Construction</div>

        <ul>
            <li><a href="#home">หน้าแรก</a></li>
            <li><a href="#services">บริการ</a></li>
            <li><a href="#contact">ติดต่อ</a></li>
        </ul>
    </nav>
</header>

<section class="hero" id="home">
    <div class="hero-content">
        <h1>บริษัทรับสร้างบ้านและก่อสร้างครบวงจร</h1>
        <p>รับสร้างบ้าน รีโนเวท รับเขียนแบบ และรับตรวจบ้าน โดยทีมงานมืออาชีพ</p>
        <a href="#contact" class="btn">ขอใบเสนอราคา</a>
    </div>
</section>

<section id="services">
    <h2>บริการของเรา</h2>

    <div class="services">

        <div class="card">
            <h3>🏠 รับสร้างบ้าน</h3>
            <p>สร้างบ้านตามงบประมาณ พร้อมควบคุมงานโดยทีมวิศวกรและสถาปนิก</p>
        </div>

        <div class="card">
            <h3>🔨 รีโนเวท</h3>
            <p>รีโนเวทบ้าน อาคาร ร้านค้า และต่อเติมทุกประเภท</p>
        </div>

        <div class="card">
            <h3>📐 รับเขียนแบบ</h3>
            <p>ออกแบบและเขียนแบบบ้าน 2D และ 3D ตามความต้องการของลูกค้า</p>
        </div>

        <div class="card">
            <h3>🔍 รับตรวจบ้าน</h3>
            <p>ตรวจรับบ้านใหม่ ตรวจงานก่อนโอน พร้อมรายงานผลละเอียด</p>
        </div>

    </div>
</section>

<section id="contact">
    <h2>ติดต่อเรา</h2>
    <p style="text-align:center;">
        📞 โทร: 08X-XXX-XXXX<br>
        📧 Email: info@abcconstruction.com<br>
        📍 ขอนแก่น ประเทศไทย
    </p>
</section>

<footer>
    <p>© 2026 ABC Construction. All Rights Reserved.</p>
</footer>

</body>
</html>
