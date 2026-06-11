<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Ima | Portfolio</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}
body{
    background:linear-gradient(135deg,#fdf2ff,#f7f0ff,#fff5f8);
    color:#333;
    overflow-x:hidden;
}
.container{
    width:90%;
    max-width:1200px;
    margin:auto;
}
header{
    min-height:100vh;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    position:relative;
}
.hero{
    background:rgba(255,255,255,0.35);
    backdrop-filter:blur(15px);
    padding:50px;
    border-radius:30px;
    box-shadow:0 15px 40px rgba(0,0,0,0.08);
    max-width:800px;
}
.hero img{
    width:180px;
    height:180px;
    border-radius:50%;
    object-fit:cover;
    border:6px solid white;
    margin-bottom:20px;
}
.hero h1{
    font-size:3rem;
    color:#7d3cff;
}
.hero h3{
    color:#555;
    margin:10px 0;
    font-weight:500;
}
.hero p{
    margin-top:15px;
    line-height:1.8;
}
.btn{
    display:inline-block;
    margin-top:25px;
    padding:12px 30px;
    background:linear-gradient(45deg,#8b5cf6,#ec4899);
    color:white;
    text-decoration:none;
    border-radius:50px;
    transition:.3s;
}
.btn:hover{
    transform:translateY(-3px);
}
section{
    padding:80px 0;
}
.title{
    text-align:center;
    margin-bottom:50px;
}
.title h2{
    font-size:2.3rem;
    color:#7d3cff;
}
.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:25px;
}
.card{
    background:rgba(255,255,255,0.6);
    backdrop-filter:blur(10px);
    border-radius:20px;
    padding:25px;
    box-shadow:0 10px 25px rgba(0,0,0,0.08);
    transition:.3s;
}
.card:hover{
    transform:translateY(-8px);
}
.card h3{
    color:#7d3cff;
    margin-bottom:10px;
}
.card p{
    line-height:1.8;
}
.timeline{
    max-width:900px;
    margin:auto;
}
.timeline-item{
    background:white;
    margin-bottom:20px;
    padding:25px;
    border-left:5px solid #8b5cf6;
    border-radius:15px;
    box-shadow:0 8px 20px rgba(0,0,0,0.05);
}
.timeline-item h3{
    color:#7d3cff;
}
.contact{
    text-align:center;
}
.contact-box{
    background:rgba(255,255,255,0.7);
    padding:40px;
    border-radius:25px;
    max-width:700px;
    margin:auto;
    box-shadow:0 10px 30px rgba(0,0,0,0.08);
}
footer{
    text-align:center;
    padding:30px;
    color:#777;
}
.decor1{
    position:fixed;
    width:300px;
    height:300px;
    background:#d8b4fe;
    border-radius:50%;
    filter:blur(100px);
    top:-50px;
    left:-100px;
    z-index:-1;
}
.decor2{
    position:fixed;
    width:300px;
    height:300px;
    background:#f9a8d4;
    border-radius:50%;
    filter:blur(100px);
    bottom:-50px;
    right:-100px;
    z-index:-1;
}
@media(max-width:768px){
    .hero h1{
        font-size:2rem;
    }
}
</style>
</head>

<body>

<div class="decor1"></div>
<div class="decor2"></div>

<header>
    <div class="hero">
        <img src="foto.jpg" alt="Ima">
        <h1>Ima</h1>
        <h3>Mahasiswa</h3>
        <p>
            Selamat datang di portfolio saya. Website ini berisi informasi
            tentang profil, pendidikan, pengalaman, keterampilan, dan berbagai
            pencapaian yang saya miliki.
        </p>
        <a href="#about" class="btn">Lihat Selengkapnya</a>
    </div>
</header>

</body>
</html>
