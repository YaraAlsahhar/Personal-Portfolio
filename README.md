<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ملف أعمالي | TikTok Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@300;400;600;700;800&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Cairo',sans-serif;
}

body{
    background:#0f172a;
    color:white;
}

header{
    min-height:55vh;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    padding:40px;
    background:linear-gradient(135deg,#0f172a,#1e293b,#020617);
}

.hero h1{
    font-size:55px;
    margin-bottom:15px;
}

.hero p{
    color:#94a3b8;
    font-size:18px;
}

.container{
    width:90%;
    max-width:1400px;
    margin:auto;
}

.section-title{
    text-align:center;
    font-size:35px;
    margin:60px 0 40px;
}

.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(320px,1fr));
    gap:25px;
    margin-bottom:80px;
}

.card{
    background:#1e293b;
    border-radius:20px;
    overflow:hidden;
    transition:0.3s;
    border:1px solid rgba(255,255,255,.05);
}

.card:hover{
    transform:translateY(-8px);
    box-shadow:0 20px 40px rgba(0,0,0,.4);
}

.thumbnail{
    width:100%;
    height:240px;
    object-fit:cover;
}

.content{
    padding:20px;
}

.video-title{
    font-size:22px;
    margin-bottom:15px;
    font-weight:700;
}

.stats{
    display:flex;
    justify-content:space-between;
    margin-bottom:20px;
}

.stat{
    background:#334155;
    padding:10px 15px;
    border-radius:12px;
    font-size:15px;
}

.btn{
    display:block;
    text-align:center;
    text-decoration:none;
    background:#ec4899;
    color:white;
    padding:14px;
    border-radius:12px;
    font-weight:bold;
    transition:0.3s;
}

.btn:hover{
    background:#db2777;
}

footer{
    text-align:center;
    padding:30px;
    color:#94a3b8;
    border-top:1px solid rgba(255,255,255,.08);
}
</style>

</head>
<body>

<header>
    <div class="hero">
        <h1>ملف أعمالي</h1>
        <p>
            صانع محتوى متخصص في صناعة المقاطع القصيرة وتحقيق ملايين المشاهدات على TikTok
        </p>
    </div>
</header>

<section class="container">

    <h2 class="section-title">أفضل الأعمال</h2>

    <div class="grid">

        <!-- الفيديو 1 -->
        <div class="card">
            <img src="thumbnail1.jpg" class="thumbnail">

            <div class="content">

                <h3 class="video-title">
                    مقطع ترند حقق انتشاراً واسعاً
                </h3>

                <div class="stats">
                    <div class="stat">👁 2.5M</div>
                    <div class="stat">❤️ 180K</div>
                </div>

                <a href="https://www.tiktok.com/" target="_blank" class="btn">
                    مشاهدة المقطع
                </a>

            </div>
        </div>

        <!-- الفيديو 2 -->
        <div class="card">
            <img src="thumbnail2.jpg" class="thumbnail">

            <div class="content">

                <h3 class="video-title">
                    فيديو تسويقي لعلامة تجارية
                </h3>

                <div class="stats">
                    <div class="stat">👁 1.8M</div>
                    <div class="stat">❤️ 125K</div>
                </div>

                <a href="https://www.tiktok.com/" target="_blank" class="btn">
                    مشاهدة المقطع
                </a>

            </div>
        </div>

        <!-- الفيديو 3 -->
        <div class="card">
            <img src="thumbnail3.jpg" class="thumbnail">

            <div class="content">

                <h3 class="video-title">
                    محتوى ترفيهي
                </h3>

                <div class="stats">
                    <div class="stat">👁 3.2M</div>
                    <div class="stat">❤️ 240K</div>
                </div>

                <a href="https://www.tiktok.com/" target="_blank" class="btn">
                    مشاهدة المقطع
                </a>

            </div>
        </div>

    </div>

</section>

<footer>
    © 2026 جميع الحقوق محفوظة
</footer>

</body>
</html>
