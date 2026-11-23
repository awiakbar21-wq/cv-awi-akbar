# cv-awi-akbar
Website CV Profesional Awi Akbar Jaelani

<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CV | Awi Akbar Jaelani</title>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  scroll-behavior: smooth;
}

body {
  font-family: Arial, sans-serif;
  background: #f3f6fc;
  color: #202b3c;
  line-height: 1.7;
}

header {
  background: #101d35;
  color: white;
  padding: 18px 8%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  position: sticky;
  top: 0;
  z-index: 10;
}

.logo {
  font-size: 22px;
  font-weight: bold;
  color: #55b5ff;
}

nav a {
  color: white;
  text-decoration: none;
  margin-left: 22px;
  font-size: 14px;
}

nav a:hover {
  color: #55b5ff;
}

.hero {
  min-height: 490px;
  background: linear-gradient(120deg,#101d35,#174b79);
  color: white;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 70px 10%;
  flex-wrap: wrap;
  gap: 30px;
}

.hero-text {
  max-width: 570px;
}

.hero h1 {
  font-size: 42px;
  margin: 12px 0;
}

.hero h1 span {
  color: #55b5ff;
}

.hero p {
  color: #d5e5f5;
}

.tag {
  color: #55b5ff;
  font-weight: bold;
  letter-spacing: 2px;
}

.profile {
  width: 210px;
  height: 210px;
  border-radius: 50%;
  border: 5px solid #55b5ff;
  object-fit: cover;
  background: #dce8f5;
}

.btn {
  display: inline-block;
  margin-top: 25px;
  padding: 12px 24px;
  border-radius: 8px;
  background: #55b5ff;
  color: #101d35;
  text-decoration: none;
  font-weight: bold;
  transition: .3s;
}

.btn:hover {
  background: white;
  transform: translateY(-3px);
}

section {
  padding: 65px 10%;
}

.section-title {
  text-align: center;
  font-size: 29px;
  color: #142b4c;
  margin-bottom: 35px;
}

.card {
  background: white;
  padding: 28px;
  border-radius: 14px;
  box-shadow: 0 5px 20px rgba(0,0,0,.06);
  margin-bottom: 20px;
}

.card h3 {
  color: #174b79;
  margin-bottom: 12px;
}

.info {
  display: grid;
  grid-template-columns: repeat(2,1fr);
  gap: 15px;
}

.info p {
  padding: 12px;
  background: #f3f6fc;
  border-radius: 8px;
}

.skills {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
}

.skills span {
  background: #e2f1ff;
  color: #14548b;
  padding: 10px 17px;
  border-radius: 20px;
  font-weight: bold;
  font-size: 14px;
}

.contact {
  text-align: center;
  background: #101d35;
  color: white;
}

.contact .section-title {
  color: white;
}

.contact p {
  margin: 10px;
}

footer {
  text-align: center;
  padding: 20px;
  background: #091326;
  color: #aebbd0;
  font-size: 13px;
}

@media(max-width:700px) {
  header {
    flex-direction: column;
    gap: 12px;
  }

  nav a {
    margin: 0 6px;
    font-size: 12px;
  }

  .hero {
    text-align: center;
    justify-content: center;
    padding: 55px 7%;
  }

  .hero h1 {
    font-size: 32px;
  }

  .profile {
    width: 170px;
    height: 170px;
  }

  .info {
    grid-template-columns: 1fr;
  }

  section {
    padding: 50px 7%;
  }
}
</style>
</head>

<body>

<header>
  <div class="logo">AWI JAELANI.</div>
  <nav>
    <a href="#home">Home</a>
    <a href="#about">Profil</a>
    <a href="#education">Pendidikan</a>
    <a href="#skills">Keahlian</a>
    <a href="#contact">Kontak</a>
  </nav>
</header>

<div class="hero" id="home">
  <div class="hero-text">
    <div class="tag">PERSONAL CURRICULUM VITAE</div>
    <h1>Halo, Saya <span>Awi Akbar Jaelani</span></h1>
    <p>
      Siswa Teknik Komputer dan Jaringan (TKJ)
      yang memiliki minat dalam dunia teknologi,
      komputer, jaringan, dan pengembangan digital.
    </p>
    <a href="#about" class="btn">Lihat Profil Saya</a>
  </div>

  <!-- Ganti URL FOTO dengan foto pribadi -->
  <img class="profile"
  src="https://placehold.co/400x400/174b79/ffffff?text=FOTO+AWI"
  alt="Foto Awi Akbar Jaelani">
</div>

<section id="about">
  <h2 class="section-title">Tentang Saya</h2>
  <div class="card">
    <h3>Profil Pribadi</h3>
    <p>
      Saya adalah seorang pelajar SMK Karya Guna 2 Bekasi
      jurusan Teknik Komputer dan Jaringan. Saya tertarik
      mempelajari teknologi informasi, perangkat komputer,
      serta sistem jaringan komputer.
    </p>
    <br>
    <div class="info">
      <p><b>Nama:</b> Awi Akbar Jaelani</p>
      <p><b>Tempat Lahir:</b> Bekasi</p>
      <p><b>Tanggal Lahir:</b> 6 Mei 2009</p>
      <p><b>Alamat:</b> Desa Kanayakan, Bojongmangu, Bekasi</p>
      <p><b>Telepon:</b> 085779255089</p>
      <p><b>Email:</b> barjae06@gmail.com</p>
    </div>
  </div>
</section>

<section id="education">
  <h2 class="section-title">Pendidikan</h2>
  <div class="card">
    <h3>SMK Karya Guna 2 Bekasi</h3>
    <p>Jurusan: Teknik Komputer dan Jaringan (TKJ)</p>
    <p>Jenjang: Sekolah Menengah Kejuruan</p>
  </div>
</section>

<section id="skills">
  <h2 class="section-title">Keahlian</h2>
  <div class="card">
    <div class="skills">
      <span>Komputer Dasar</span>
      <span>Microsoft Office</span>
      <span>Jaringan Komputer</span>
      <span>Instalasi Sistem Operasi</span>
      <span>HTML & CSS</span>
      <span>Troubleshooting Dasar</span>
    </div>
  </div>
</section>

<section>
  <h2 class="section-title">Tujuan Karier</h2>
  <div class="card">
    <p>
      Saya ingin terus mengembangkan kemampuan di bidang
      teknologi informasi, khususnya jaringan komputer
      dan pengembangan website, serta mendapatkan pengalaman
      baru untuk mempersiapkan diri memasuki dunia kerja.
    </p>
  </div>
</section>

<section class="contact" id="contact">
  <h2 class="section-title">Hubungi Saya</h2>
  <p>Email: barjae06@gmail.com</p>
  <p>Telepon: 085779255089</p>
  <a class="btn"
  href="https://wa.me/6285779255089">
  Hubungi via WhatsApp
  </a>
</section>

<footer>
  © 2026 Awi Akbar Jaelani | Personal CV Website
</footer>

</body>
</html>
