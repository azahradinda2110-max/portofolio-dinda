
<template>
  <div class="portfolio">
    <header class="navbar">
      <div class="navbar-inner">
        <a href="#home" class="logo">Dinda Azahra<span>.</span></a>

        <nav aria-label="Navigasi utama">
          <a href="#home">Home</a>
          <a href="#about">About</a>
          <a href="#hobbies">Hobbies</a>
          <a href="#projects">Projects</a>
          <a href="#contact">Contact</a>
        </nav>
      </div>
    </header>

    <main>
      <section id="home" class="hero">
        <div class="hero-text">
          <p class="eyebrow">HELLO, WELCOME TO MY PORTFOLIO</p>

          <h1>Hi, I'm <span>Dinda Azahra!</span></h1>

          <h2>Student of Software Engineering</h2>

          <p class="description">
           Halo! Saya Dinda, siswi kelas XI jurusan Rekayasa Perangkat Lunak (RPL).
            Saya tertarik dengan pengembangan website dan desain UI/UX. 
            Saat ini saya terus belajar membuat website yang menarik, nyaman digunakan, dan sesuai kebutuhan pengguna sebagai persiapan untuk kegiatan PKL
          </p>

          <a href="#projects" class="button">Lihat Project <span>↗</span></a>

          <div class="social-note">
            <span class="dot"></span> RPL Student · SMKN 71 Jakarta
          </div>
        </div>

        <div class="hero-visual">
          <div class="decor decor-one">✿</div>
          <div class="decor decor-two">♡</div>

          <div class="photo-frame">
           <img
  src="/foto-dinda.jpeg"
  alt="Foto Dinda"
  class="profile-photo"
/>
          </div>

          <div class="photo-caption">
            <span>✦</span>
            <div>
              <strong>It's me, Dinda!</strong>
              <p>Welcome to my little space</p>
            </div>
          </div>
        </div>
      </section>

      <section id="about" class="about section">
        <p class="eyebrow">GET TO KNOW ME</p>
        <h2 class="section-title">A Little About Me <span></span></h2>

        <p class="about-description">
         Saya adalah siswi SMK jurusan Rekayasa Perangkat Lunak yang senang mempelajari teknologi, khususnya coding dan desain website.
        </p>

        <div class="bio-grid">
          <article class="bio-card">
            <span class="bio-icon">♡</span>
            <div><p class="card-label">NAMA LENGKAP</p><h3>Dinda Azahra</h3></div>
          </article>
          <article class="bio-card">
            <span class="bio-icon">⌘</span>
            <div><p class="card-label">TANGGAL LAHIR</p><h3>21 Oktober 2009</h3></div>
          </article>
          <article class="bio-card">
            <span class="bio-icon">⌂</span>
            <div><p class="card-label">SEKOLAH</p><h3>SMKN 71 Jakarta</h3></div>
          </article>
          <article class="bio-card">
            <span class="bio-icon">✧</span>
            <div><p class="card-label">JURUSAN</p><h3>Rekayasa Perangkat Lunak</h3></div>
          </article>
        </div>

        <div class="skills">
          <span>HTML</span>
          <span>CSS</span>
          <span>JavaScript</span>
          <span>UI/UX Design</span>
          <span>Web Development</span>
          <span>Data Analysis</span>
        </div>
      </section>

      <section id="hobbies" class="hobbies section">
        <p class="eyebrow">THINGS I LOVE</p>
        <h2 class="hobbies-title">My Hobbies <span>♡</span></h2>
        <p class="hobbies-description">
          In my free time, I enjoy doing things that make me happy.
        </p>
        <div class="hobby-grid">
          <article class="hobby-card">
            <div class="hobby-icon">♫</div>
            <h3>Listening to Music</h3>
            <p>Enjoying my favorite songs.</p>
          </article>
          <article class="hobby-card">
            <div class="hobby-icon">▶</div>
            <h3>Watching Movies</h3>
            <p>Exploring different stories.</p>
          </article>
          <article class="hobby-card">
            <div class="hobby-icon">▤</div>
            <h3>Reading</h3>
            <p>Enjoying books and stories.</p>
          </article>
        </div>
      </section>
   

      <section id="projects" class="projects section">
        <p class="eyebrow">A COLLECTION OF MY WORK</p>
        <h2 class="section-title">My Projects <span>✿</span></h2>
        <p class="section-subtitle">
          Beberapa project yang saya kerjakan selama belajar.
        </p>

        <div class="project-grid">
          <article class="project-card">
            <div class="project-icon laundry">🫧</div>
            <p class="project-number">PROJECT 01</p>
            <h3>Joyness Laundry</h3>
            <p>
              Website laundry dengan informasi outlet, status cucian,
              dan reservasi layanan laundry.
            </p>
            <div class="tags">
              <span>HTML</span>
              <span>CSS</span>
              <span>UI/UX</span>
            </div>
          </article>

          <article class="project-card">
            <div class="project-icon web">⌘</div>
            <p class="project-number">PROJECT 02</p>
            <h3>Cafe Cashier Website</h3>
            <p>
             Website kasir kafe yang dibuat untuk menampilkan antarmuka kasir dengan tampilan menu dan informasi pesanan. 
            </p>
            <div class="tags">
              <span>HTML</span>
              <span>CSS</span>
              <span>Frontend</span>
            </div>
          </article>
        </div>
      </section>

      
<section id="contact" class="contact">
  <p class="section-label">GET IN TOUCH</p>
  <h2>Let's Talk!</h2>
  <p class="contact-description">
    Punya pertanyaan atau ingin mengenal lebih jauh
    tentang proyek saya? Hubungi saya melalui email
    di bawah ini.
  </p>

  <a
    href="mailto:dindaazahra2110@gmail.com"
    class="email-link"
  >
    <span class="email-icon">✉</span>
    <span>
      <small>EMAIL</small>
      <strong>dindaazahra2110@gmail.com</strong>
    </span>
  </a>
</section>

    </main>

    <footer>
      © 2026 Dinda · Made with ♡ and a little creativity.
    </footer>
  </div>
</template>

<style>
:root {
  --blue-ink: #1d3e5e;
  --blue-deep: #246fb3;
  --blue: #3288d7;
  --blue-light: #56a0e8;
  --blue-pale: #d6eaff;
  --blue-border: #bdd9f5;
  --blue-muted: #5f7892;
  --page-blue: #eaf4ff;
}

* {
  box-sizing: border-box;
  scroll-behavior: smooth;
}

body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
  background: var(--page-blue);
  color: var(--blue-ink);
}

a {
  text-decoration: none;
  color: inherit;
}

.portfolio {
  min-height: 100vh;
  overflow-x: clip;
  background:
    radial-gradient(ellipse at 8% 8%, #cfe5ff 0, transparent 32%),
    radial-gradient(ellipse at 95% 50%, #d8ebff 0, transparent 30%),
    var(--page-blue);
}

.navbar {
  position: sticky;
  top: 0;
  z-index: 10;
  width: 100%;
  padding: 0 24px;
  background: rgb(226 240 255 / 94%);
  border-bottom: 1px solid var(--blue-border);
  backdrop-filter: blur(12px);
}

.navbar-inner {
  max-width: 1200px;
  min-height: 76px;
  margin: auto;
  padding: 16px 16px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 27px;
  font-weight: 800;
  color: var(--blue-deep);
  letter-spacing: -1px;
}

.logo span,
.hero-text h1 span {
  color: var(--blue-light);
}

.navbar nav {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 12px 28px;
  font-size: 14px;
  font-weight: 600;
}

.navbar nav a {
  padding: 9px 12px;
  border-radius: 20px;
  transition: color 0.2s, background-color 0.2s, transform 0.2s;
}

.navbar nav a:hover {
  color: var(--blue-deep);
  background: #d1e6ff;
  transform: translateY(-1px);
}

.hero {
  position: relative;
  max-width: 1120px;
  min-height: 590px;
  margin: auto;
  padding: 75px 40px 95px;
  display: grid;
  grid-template-columns: 1.2fr 0.8fr;
  gap: 45px;
  align-items: center;
}

.eyebrow {
  color: var(--blue);
  font-size: 11px;
  font-weight: 800;
  letter-spacing: 3px;
  line-height: 1.8;
}

.hero-text h1 {
  margin: 16px 0;
  font-size: clamp(42px, 5vw, 65px);
  line-height: 1.12;
  letter-spacing: -2px;
}

.hero-text h2 {
  margin: 0;
  font-size: 19px;
  font-weight: 600;
}

.description {
  max-width: 510px;
  margin: 22px 0;
  color: var(--blue-muted);
  font-size: 15px;
  line-height: 1.9;
}

.button {
  display: inline-flex;
  align-items: center;
  gap: 15px;
  padding: 14px 23px;
  margin-top: 8px;
  border-radius: 30px;
  background: linear-gradient(135deg, #55a7f2, #287dc9);
  color: white;
  font-size: 14px;
  font-weight: 700;
  box-shadow: 0 10px 25px #287dc945;
  transition: transform 0.2s, box-shadow 0.2s, background 0.2s;
}

.button:hover {
  background: linear-gradient(135deg, #398fdc, #1e69ae);
  transform: translateY(-2px);
  box-shadow: 0 14px 28px #1e69ae45;
}

.social-note {
  margin-top: 30px;
  display: flex;
  align-items: center;
  gap: 9px;
  color: var(--blue-muted);
  font-size: 12px;
}

.dot {
  width: 8px;
  height: 8px;
  border-radius: 50%;
  background: var(--blue-light);
}

.hero-visual {
  position: relative;
  min-height: 460px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.hero-visual::before {
  position: absolute;
  width: 340px;
  height: 340px;
  border-radius: 50%;
  background: radial-gradient(circle, #b9d9ff 0%, #d6eaff 55%, transparent 72%);
  content: "";
}

.photo-frame {
  position: relative;
  z-index: 1;
  width: 285px;
  height: 335px;
  padding: 12px;
  border: 1px solid var(--blue-border);
  border-radius: 48% 48% 35px 35px;
  background: #eaf4ff;
  box-shadow: 0 20px 55px #246fb326;
  transform: rotate(3deg);
}

.profile-photo {
  display: block;
  width: 100%;
  height: 100%;
  border-radius: 48% 48% 27px 27px;
  object-fit: cover;
  background: #dceafa;
}

.decor {
  position: absolute;
  z-index: 1;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 50%;
  background: #e1efff;
  box-shadow: 0 8px 25px #246fb326;
}

.decor-one {
  top: 35px;
  left: 8px;
  width: 57px;
  height: 57px;
  color: var(--blue);
  font-size: 31px;
}

.decor-two {
  right: 0;
  top: 105px;
  width: 48px;
  height: 48px;
  color: var(--blue);
  font-size: 26px;
}

.photo-caption {
  position: absolute;
  bottom: 0;
  left: 50%;
  z-index: 2;
  display: flex;
  align-items: center;
  gap: 12px;
  width: max-content;
  max-width: calc(100% - 24px);
  padding: 13px 17px;
  border: 1px solid #bdd9f5;
  border-radius: 17px;
  background: linear-gradient(135deg, #eaf4ff, #dcecff);
  box-shadow: 0 12px 30px #246fb326;
  transform: translateX(-50%);
}

.photo-caption > span {
  color: var(--blue);
  font-size: 25px;
}

.photo-caption strong {
  font-size: 13px;
}

.photo-caption p {
  margin: 5px 0 0;
  color: #849bb4;
  font-size: 11px;
}

.section {
  padding: 85px 40px;
  text-align: center;
}

.about {
  background: linear-gradient(180deg, #e4f1ff 0%, #dcecff 100%);
}

.section-title {
  margin: 12px 0;
  font-size: 34px;
  letter-spacing: -1px;
}

.section-title span {
  color: var(--blue-light);
}

.about-description,
.section-subtitle {
  max-width: 650px;
  margin: 18px auto 0;
  color: var(--blue-muted);
  font-size: 15px;
  line-height: 1.9;
}


/* BIODATA */
.bio-grid {
  max-width: 760px;
  margin: 30px auto 0;
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 14px;
  text-align: left;
}
.bio-card {
  display: flex;
  align-items: center;
  gap: 14px;
  padding: 18px;
  border: 1px solid #c7def7;
  border-radius: 18px;
  background: linear-gradient(145deg, #edf6ff, #e2efff);
  box-shadow: 0 8px 24px #246fb31c;
  transition: transform 0.2s, box-shadow 0.2s, border-color 0.2s;
}
.bio-card:hover {
  transform: translateY(-3px);
  border-color: #9fc6ef;
  box-shadow: 0 13px 28px #246fb32b;
}
.bio-icon, .hobby-icon {
  width: 46px;
  height: 46px;
  flex-shrink: 0;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 14px;
  background: linear-gradient(145deg, #d5eaff, #c3dfff);
  color: var(--blue);
  font-size: 25px;
}
.card-label {
  margin: 0 0 5px;
  color: #7999bd;
  font-size: 9px;
  font-weight: 800;
  letter-spacing: 1.5px;
}
.bio-card h3 {
  margin: 0;
  color: var(--blue-ink);
  font-size: 14px;
  line-height: 1.5;
}

/* HOBI */
.hobbies {
  background: linear-gradient(135deg, #d5e9ff 0%, #e4f1ff 52%, #cfe4fb 100%);
}
.hobbies-title {
  margin: 12px 0;
  color: var(--blue-ink);
  font-size: 34px;
  letter-spacing: -0.5px;
}
.hobbies-title span { color: var(--blue-light); }
.hobbies-description {
  max-width: 650px;
  margin: 18px auto 0;
  color: var(--blue-muted);
  font-size: 15px;
  line-height: 1.9;
}
.hobby-grid {
  max-width: 900px;
  margin: 38px auto 0;
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 22px;
}
.hobby-card {
  padding: 30px 22px;
  border: 1px solid #bfd9f4;
  border-radius: 20px;
  background: linear-gradient(145deg, #eaf4ff 0%, #dcecff 100%);
  box-shadow: 0 10px 30px #246fb31c;
  transition: transform 0.25s, box-shadow 0.25s, border-color 0.25s;
}
.hobby-card:hover {
  transform: translateY(-6px);
  border-color: #97c1ec;
  box-shadow: 0 18px 34px #246fb333;
}
.hobby-icon {
  margin: 0 auto 18px;
  width: 58px;
  height: 58px;
  font-size: 27px;
}
.hobby-card h3 {
  margin: 0;
  color: var(--blue-ink);
  font-size: 16px;
}
.hobby-card p {
  margin: 10px 0 0;
  color: var(--blue-muted);
  font-size: 13px;
  line-height: 1.7;
}

.skills {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 10px;
  margin: 28px auto 0;
}

.skills span,
.tags span {
  padding: 9px 15px;
  border: 1px solid var(--blue-border);
  border-radius: 30px;
  background: linear-gradient(135deg, #e8f3ff, #d6eaff);
  color: var(--blue-deep);
  font-size: 12px;
  font-weight: 600;
}

.projects {
  background: linear-gradient(180deg, #dcecff 0%, #cfe4fb 100%);
}

.project-grid {
  max-width: 820px;
  margin: 38px auto 0;
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 22px;
  text-align: left;
}

.project-card {
  padding: 27px;
  border: 1px solid #b8d4f1;
  border-radius: 23px;
  background: linear-gradient(145deg, #e8f3ff 0%, #d7eaff 100%);
  box-shadow: 0 10px 30px #246fb31f;
  transition: transform 0.25s, box-shadow 0.25s, border-color 0.25s;
}

.project-card:hover {
  transform: translateY(-6px);
  border-color: #91bce9;
  box-shadow: 0 18px 36px #246fb333;
}

.project-icon {
  width: 56px;
  height: 56px;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 17px;
  font-size: 26px;
}

.laundry {
  background: linear-gradient(135deg, #cde7ff, #b4d9ff);
}

.web {
  background: #f0eaff;
  color: #8c80bd;
  font-size: 30px;
}

.project-number {
  margin: 23px 0 8px;
  color: #7999bd;
  font-size: 10px;
  font-weight: 800;
  letter-spacing: 2px;
}

.project-card h3 {
  margin: 0;
  font-size: 21px;
}

.project-card > p:not(.project-number) {
  color: var(--blue-muted);
  font-size: 13px;
  line-height: 1.8;
}

.tags {
  display: flex;
  flex-wrap: wrap;
  gap: 7px;
  margin-top: 20px;
}

.tags span {
  padding: 7px 11px;
  font-size: 10px;
}


.contact {
  padding: 60px 24px;
  text-align: center;
  background: linear-gradient(135deg, #cfe5ff, #e0efff 55%, #c4ddf8);
  border-radius: 24px;
  border: 1px solid #b5d2ef;
}

.section-label {
  color: var(--blue-deep);
  font-size: 12px;
  font-weight: bold;
  letter-spacing: 2px;
}

.contact h2 {
  color: var(--blue-ink);
  font-size: 36px;
  margin: 12px 0;
}

.contact-description {
  color: #526f8c;
  max-width: 450px;
  margin: 0 auto 28px;
  line-height: 1.8;
}

.email-link {
  display: inline-flex;
  align-items: center;
  gap: 14px;
  padding: 14px 20px;
  border-radius: 16px;
  background: linear-gradient(135deg, #e8f3ff, #d5e9ff);
  color: var(--blue-ink);
  text-decoration: none;
  text-align: left;
  box-shadow: 0 8px 22px #246fb326;
  transition: transform 0.2s, box-shadow 0.2s;
}

.email-link:hover {
  transform: translateY(-3px);
  box-shadow: 0 13px 28px #246fb333;
}

.email-icon {
  background: linear-gradient(135deg, #cde4ff, #b7d8ff);
  color: var(--blue-deep);
  padding: 12px;
  border-radius: 12px;
  font-size: 22px;
}

.email-link small,
.email-link strong {
  display: block;
}

.email-link small {
  color: var(--blue-deep);
  margin-bottom: 5px;
}

footer {
  padding: 24px;
  background: linear-gradient(135deg, #c5ddf7, #d5e8fc);
  color: #42688e;
  text-align: center;
  font-size: 12px;
}

@media (max-width: 700px) {
  .navbar {
    padding: 0 16px;
  }

  .navbar-inner {
    min-height: 0;
    padding: 14px 0;
    flex-direction: column;
    gap: 14px;
  }

  .logo {
    font-size: 23px;
  }

  .navbar nav {
    gap: 10px 18px;
    font-size: 13px;
  }

  .hero {
    grid-template-columns: 1fr;
    padding: 50px 25px 65px;
    gap: 30px;
  }

  .hero-text h1 {
    font-size: 46px;
  }

  .hero-visual {
    min-height: 430px;
  }

  .photo-frame {
    width: 250px;
    height: 300px;
  }

  .decor-one {
    left: 8%;
  }

  .decor-two {
    right: 7%;
  }

  .section {
    padding: 65px 22px;
  }

  .section-title {
    font-size: 29px;
  }

  .hobbies-title {
    font-size: 29px;
  }

  .hobby-grid {
    grid-template-columns: 1fr;
    max-width: 420px;
  }

  .project-grid {
    grid-template-columns: 1fr;
  }
}

@media (prefers-reduced-motion: reduce) {
  *,
  *::before,
  *::after {
    scroll-behavior: auto !important;
    transition-duration: 0.01ms !important;
  }
}
</style>
