kurangin yapping perbanyak praying


<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#10110f">
<meta name="description" content="Website pribadi REZKY ADITYA, siswa XII TKJ 1 yang menyukai sepak bola, jalan-jalan, dan Formula 1.">
<title>REZKY ADITYA | Personal Website</title>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  scroll-behavior: smooth;
}

:root {
  --bg: #10110f;
  --card: #191a17;
  --green: #c9fa65;
  --text: #f5f5f0;
  --muted: #bcbeb5;
}

body {
  font-family: Arial, Helvetica, sans-serif;
  background: var(--bg);
  color: var(--text);
  line-height: 1.7;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 18px 7%;
  border-bottom: 1px solid #333;
  position: sticky;
  top: 0;
  background: rgba(16,17,15,.96);
  backdrop-filter: blur(10px);
  z-index: 100;
}

.logo {
  font-size: 20px;
  font-weight: bold;
  color: var(--green);
  letter-spacing: 1px;
}

nav {
  display: flex;
  gap: 13px;
}

nav a {
  color: white;
  text-decoration: none;
  font-size: 12px;
}

nav a:hover {
  color: var(--green);
}

section {
  padding: 70px 7%;
  scroll-margin-top: 65px;
}

.hero {
  min-height: 88vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  background:
    radial-gradient(ellipse at 90% 20%,
    rgba(201,250,101,.09), transparent 55%);
}

.tag {
  color: var(--green);
  font-size: 12px;
  letter-spacing: 2px;
  margin-bottom: 18px;
}

h1 {
  font-size: clamp(40px, 10vw, 75px);
  line-height: 1.12;
  margin-bottom: 22px;
  overflow-wrap: anywhere;
}

h1 span {
  color: var(--green);
}

p {
  color: var(--muted);
  margin-bottom: 18px;
}

.hero p {
  max-width: 520px;
}

.btn {
  display: inline-block;
  padding: 11px 19px;
  margin: 7px 5px 7px 0;
  background: var(--green);
  color: var(--bg);
  text-decoration: none;
  border-radius: 30px;
  font-weight: bold;
  font-size: 14px;
  border: 1px solid var(--green);
  cursor: pointer;
  transition: .25s;
}

.btn:hover {
  transform: translateY(-2px);
}

.btn-outline {
  background: transparent;
  color: var(--green);
}

.profile {
  display: block;
  width: 100%;
  max-width: 320px;
  height: 350px;
  object-fit: cover;
  object-position: center;
  border-radius: 18px;
  margin-top: 28px;
  border: 1px solid #36382f;
  background: var(--card);
}

h2 {
  font-size: clamp(30px, 7vw, 42px);
  line-height: 1.2;
  margin-bottom: 22px;
}

.card {
  padding: 22px;
  margin-top: 18px;
  background: var(--card);
  border: 1px solid #36382f;
  border-radius: 16px;
  overflow: hidden;
}

.card h3 {
  color: var(--green);
  margin-bottom: 10px;
}

.card img {
  display: block;
  width: 100%;
  height: 200px;
  object-fit: cover;
  border-radius: 10px;
  margin-bottom: 15px;
  background: #252720;
}

.info {
  display: grid;
  gap: 12px;
  margin-top: 20px;
}

.info-item {
  padding: 15px;
  border: 1px solid #36382f;
  border-radius: 10px;
  overflow-wrap: anywhere;
}

.info-item strong {
  display: block;
  color: var(--green);
  font-size: 12px;
  letter-spacing: 1px;
  margin-bottom: 5px;
}

.info-item a {
  color: white;
  text-decoration: none;
}

.info-item a:hover {
  color: var(--green);
}

.social {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 20px;
}

footer {
  text-align: center;
  padding: 25px 7%;
  border-top: 1px solid #333;
  color: #888;
  font-size: 13px;
}

@media (min-width: 700px) {
  section {
    padding-left: 12%;
    padding-right: 12%;
  }

  header {
    padding-left: 12%;
    padding-right: 12%;
  }

  .hero {
    min-height: 90vh;
  }

  .hobi-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 15px;
  }

  .hobi-grid .card {
    margin-top: 0;
  }

  .hobi-grid .card:first-child {
    grid-column: span 2;
  }
}
</style>
</head>

<body>

<header>
  <div class="logo">REZKY.</div>

  <nav aria-label="Navigasi utama">
    <a href="#tentang">Profil</a>
    <a href="#hobi">Hobi</a>
    <a href="#kontak">Kontak</a>
  </nav>
</header>

<!-- HALAMAN UTAMA -->
<section class="hero" id="home">
  <div class="tag">✦ PERSONAL WEBSITE</div>

  <h1>
    HALO,<br>
    SAYA <span>REZKY ADITYA.</span>
  </h1>

  <p>
    Selamat datang di website pribadi saya.
    Kenali saya lebih dekat melalui profil,
    hobi, dan media sosial saya.
  </p>

  <div>
    <a href="#tentang" class="btn">Tentang Saya ↓</a>
    <a href="#kontak" class="btn btn-outline">
      Hubungi Saya
    </a>
  </div>

  <!-- Simpan foto utama dengan nama foto.jpg -->
  <img src="foto.jpg"
       alt="Foto profil REZKY ADITYA"
       class="profile">
</section>

<!-- PROFIL -->
<section id="tentang">
  <div class="tag">01 — PROFIL</div>
  <h2>Tentang Saya.</h2>

  <div class="card">
    <h3>REZKY ADITYA</h3>

    <p>
      Halo semuanya! Nama saya REZKY ADITYA.
      Saya adalah siswa kelas XII TKJ 1.
      Ini adalah website pribadi saya untuk
      memperkenalkan diri, berbagi hobi,
      dan menunjukkan hal-hal yang saya sukai.
    </p>
  </div>

  <div class="info">
    <div class="info-item">
      <strong>NAMA LENGKAP</strong>
      REZKY ADITYA
    </div>

    <div class="info-item">
      <strong>KELAS</strong>
      XII TKJ 1
    </div>

    <div class="info-item">
      <strong>HOBI</strong>
      Bermain Bola, Jalan jalan, dan Menonton Formula 1
    </div>
  </div>
</section>

<!-- HOBI -->
<section id="hobi">
  <div class="tag">02 — AKTIVITAS</div>
  <h2>Hal yang Saya Suka.</h2>

  <p>
    Tiga hal yang membuat waktu luang saya lebih seru.
  </p>

  <div class="hobi-grid">

    <div class="card">
      <img src="bola.jpg" alt="Bermain sepak bola">
      <h3>01. Bermain Bola ⚽</h3>
      <p>
        Menikmati permainan sepak bola,
        berolahraga bersama teman,
        dan menjunjung tinggi sportivitas.
      </p>
    </div>

    <div class="card">
      <img src="jalan.jpg" alt="Jalan-jalan">
      <h3>02. Jalan-Jalan 🌄</h3>
      <p>
        Menjelajahi tempat baru, menikmati
        pemandangan, dan mencari pengalaman seru.
      </p>
    </div>

    <div class="card">
      <img src="f1.jpg" alt="Formula 1">
      <h3>03. Menonton Formula 1 🏎️</h3>
      <p>
        Menikmati balapan, strategi tim,
        kecepatan mobil, dan persaingan
        seru di lintasan Formula 1.
      </p>
    </div>

  </div>
</section>

<!-- KONTAK -->
<section id="kontak">
  <div class="tag">03 — KONTAK</div>
  <h2>Mari Terhubung.</h2>

  <p>
    Terima kasih sudah mengunjungi website saya.
    Kamu bisa menghubungi atau mengikuti saya
    melalui media sosial berikut.
  </p>

  <div class="info">

    <div class="info-item">
      <strong>WHATSAPP</strong>
      <a href="https://wa.me/6283897256809"
         target="_blank"
         rel="noopener noreferrer">
        0838-9725-6809 ↗
      </a>
    </div>

    <div class="info-item">
      <strong>INSTAGRAM</strong>
      <a href="https://instagram.com/kyy_cavalry"
         target="_blank"
         rel="noopener noreferrer">
        @kyy_cavalry ↗
      </a>
    </div>

  </div>

  <div class="social">
    <a class="btn"
       href="https://wa.me/6283897256809"
       target="_blank"
       rel="noopener noreferrer">
      Chat WhatsApp
    </a>

    <a class="btn btn-outline"
       href="https://instagram.com/kyy_cavalry"
       target="_blank"
       rel="noopener noreferrer">
      Instagram Saya
    </a>
  </div>
</section>

<footer>
  © 2026 REZKY ADITYA. All rights reserved.
</footer>

</body>
</html>
