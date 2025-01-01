<template>
  <div>
    <!-- Hero Section -->
    <section class="hero-section text-center text-white py-5">
      <div class="container">
        <h1 class="display-4 mb-4">Selamat Datang di SMKN 4 Tasikmalaya</h1>
        <p class="lead mb-4">Temukan informasi terbaru mengenai kegiatan, prestasi, dan program unggulan kami</p>
      </div>
    </section>

    <!-- Gambar di atas Sambutan Kepala Sekolah -->
    <section class="header-image-section">
      <img src="~/assets/img/home.jpg" alt="Selamat Datang Di Website SMKN 4" class="img-fluid w-100" />
    </section>

    <!-- Sambutan Kepala Sekolah -->
    <section class="sambutan-section py-5" id="sambutan">
      <div class="container text-center">
        <h2 class="mb-4">Sambutan Kepala Sekolah</h2>
        <div class="row align-items-center">
          <div class="col-md-4">
            <img src="~/assets/img/kepsek.png" alt="Kepala Sekolah" class="img-fluid rounded-circle" />
          </div>
          <div class="col-md-8">
            <p class="lead">Selamat datang di website resmi SMKN 4 Tasikmalaya. Kami dengan bangga mempersembahkan berbagai informasi tentang sekolah kami, kegiatan, dan prestasi yang telah kami capai.</p>
            <p><small class="text-muted">Kepala Sekolah, SMKN 4 Tasikmalaya</small></p>
          </div>
        </div>
      </div>
    </section>

    <!-- Berita Terbaru -->
    <section class="berita-section py-5" id="berita">
      <div class="container text-center">
        <h2 class="mb-4">Berita Terbaru</h2>
        <div class="row">
          <div class="col-md-4 mb-4">
            <div class="card">
              <img src="~/assets/img/expo.webp" class="card-img-top" alt="Expo" />
              <div class="card-body">
                <h5 class="card-title">Expo Sekolah</h5>
                <p class="card-text">Update terbaru tentang Expo sekolah kami, kegiatan yang menarik dan penuh informasi.</p>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-4">
            <div class="card">
              <img src="~/assets/img/fair.jpg" class="card-img-top" alt="Job Fair" />
              <div class="card-body">
                <h5 class="card-title">Job Fair</h5>
                <p class="card-text">Dapatkan informasi terbaru mengenai Job Fair yang akan diadakan oleh sekolah.</p>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-4">
            <div class="card">
              <img src="~/assets/img/binsik.jpg" class="card-img-top" alt="Binsik" />
              <div class="card-body">
                <h5 class="card-title">Binsik</h5>
                <p class="card-text">Kegiatan binsik adalah bimbingan fisik untuk kelas 12 yang bertujuan untuk mempersiapkan ujian akhir.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Jurusan Section -->
    <section id="jurusan" class="container mt-5">
      <div class="row">
        <div class="col text-center">
          <h2 class="fw-bold">Jurusan</h2>
          <p class="text-muted">"SMKN 4 Tasikmalaya menyediakan berbagai jurusan yang menarik dan berkualitas."</p>
        </div>
      </div>

      <!-- Row Card Jurusan -->
      <div class="row mt-4">
        <!-- Card TKJ -->
        <div class="col-lg-4 col-md-6 mb-4">
          <div class="shadow card h-100 card-hover rounded-lg">
            <div class="card-body text-center bg-primary rounded-top">
              <img src="~/assets/img/tkj.png" alt="Logo Sekolah" width="40" height="45" class="me-2">
              <h5 class="card-title">Teknik Komputer dan Jaringan (TKJ)</h5>
              <p class="card-text">Mahir dalam jaringan komputer dan teknologi informasi. Jurusan ini fokus pada penguasaan konsep dan praktik dalam membangun, mengelola, dan mengamankan jaringan komputer.</p>
              <p class="card-text"><strong>Jumlah Murid: 120</strong></p>
            </div>
          </div>
        </div>

        <!-- Card RPL -->
        <div class="col-lg-4 col-md-6 mb-4">
          <div class="shadow card h-100 card-hover rounded-lg">
            <div class="card-body text-center bg-success rounded-top">
              <img src="~/assets/img/rpl.png" alt="Logo Sekolah" width="40" height="45" class="me-2">
              <h5 class="card-title">Rekayasa Perangkat Lunak (RPL)</h5>
              <p class="card-text">Ahli dalam pengembangan perangkat lunak modern. Jurusan ini mempelajari cara merancang, mengembangkan, dan memelihara perangkat lunak, termasuk aplikasi berbasis desktop, web, dan mobile.</p>
              <p class="card-text"><strong>Jumlah Murid: 100</strong></p>
            </div>
          </div>
        </div>

        <!-- Card DKV -->
        <div class="col-lg-4 col-md-6 mb-4">
          <div class="shadow card h-100 card-hover rounded-lg">
            <div class="card-body text-center bg-warning rounded-top">
              <img src="~/assets/img/dkv.png" alt="Logo Sekolah" width="40" height="45" class="me-2">
              <h5 class="card-title">Desain Komunikasi Visual (DKV)</h5>
              <p class="card-text">Kreatif dalam seni desain dan komunikasi visual. Jurusan ini mengajarkan seni dan teknik dalam menciptakan desain visual yang komunikatif dan menarik.</p>
              <p class="card-text"><strong>Jumlah Murid: 90</strong></p>
            </div>
          </div>
        </div>

        <!-- Card TBSM -->
        <div class="col-lg-6 col-md-6 mb-4">
          <div class="shadow card h-100 card-hover rounded-lg">
            <div class="card-body text-center bg-danger rounded-top">
              <img src="~/assets/img/tsm.png" alt="Logo Sekolah" width="40" height="45" class="me-2">
              <h5 class="card-title">Teknik Bisnis Sepeda Motor (TBSM)</h5>
              <p class="card-text">Ahli dalam perbaikan dan manajemen bisnis sepeda motor. Jurusan ini mempelajari teknik perawatan, perbaikan, dan modifikasi sepeda motor, sekaligus menanamkan keterampilan kewirausahaan.</p>
              <p class="card-text"><strong>Jumlah Murid: 80</strong></p>
            </div>
          </div>
        </div>

        <!-- Card TOI -->
        <div class="col-lg-6 col-md-6 mb-4">
          <div class="shadow card h-100 card-hover rounded-lg">
            <div class="card-body text-center bg-secondary rounded-top">
              <img src="~/assets/img/toi.png" alt="Logo Sekolah" width="40" height="45" class="me-2">
              <h5 class="card-title">Teknik Otomasi Industri (TOI)</h5>
              <p class="card-text">Mahir dalam sistem otomatisasi dan teknologi industri. Jurusan ini berfokus pada teknologi otomotif yang diterapkan dalam skala industri.</p>
              <p class="card-text"><strong>Jumlah Murid: 70</strong></p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer Section -->
    <footer class="bg-dark text-white text-center py-4">
      <p>&copy; 2024 SMKN 4 Tasikmalaya | Semua Hak Cipta Dilindungi</p>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
  data() {
    return {
      jurusan: [
        { name: "Teknik Komputer dan Jaringan (TKJ)", description: "Mahir dalam jaringan komputer dan teknologi informasi.", students: 120 },
        { name: "Rekayasa Perangkat Lunak (RPL)", description: "Ahli dalam pengembangan perangkat lunak modern.", students: 100 },
        { name: "Desain Komunikasi Visual (DKV)", description: "Kreatif dalam seni desain dan komunikasi visual.", students: 90 },
        { name: "Teknik Bisnis Sepeda Motor (TBSM)", description: "Ahli dalam perbaikan dan manajemen bisnis sepeda motor.", students: 80 },
        { name: "Teknik Otomasi Industri (TOI)", description: "Mahir dalam sistem otomatisasi dan teknologi industri.", students: 70 }
      ]
    };
  }
};
</script>

<style scoped>
/* Global Styles */
body {
  font-family: 'Arial', sans-serif;
}

/* Hero Section */
.hero-section {
  background: url('~/assets/img/hero-bg.jpg') no-repeat center center/cover;
  color: white;
  padding: 5rem 0;
}

.hero-section h1 {
  font-size: 3rem;
  font-weight: bold;
}

.hero-section .lead {
  font-size: 1.25rem;
}

/* Gambar di atas Sambutan Kepala Sekolah */
.header-image-section img {
  width: 100%;
  height: auto;
  margin-bottom: 2rem;
}

/* Sambutan Kepala Sekolah Section */
.sambutan-section {
  background-color: #f8f9fa;
}

.sambutan-section h2 {
  font-size: 2.5rem;
  font-weight: bold;
  color: #333;
}

/* Berita Terbaru Section */
.berita-section h2 {
  font-size: 2.5rem;
  font-weight: bold;
  color: #333;
}

.card {
  border-radius: 10px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s;
}

.card:hover {
  transform: translateY(-5px);
}

.card-img-top {
  height: 200px;
  object-fit: cover;
}

/* Footer */
footer {
  background-color: #343a40;
}

footer p {
  margin: 0;
  color: #adb5bd;
}

/* Card Jurusan Styles */
.card-body {
  padding: 25px;
}

.card-title {
  font-weight: bold;
  font-size: 1.3rem;
}

.card-text {
  font-size: 1rem;
  line-height: 1.5;
}

.bg-primary {
  background-color: #007bff !important;
}

.bg-success {
  background-color: #28a745 !important;
}

.bg-warning {
  background-color: #ffc107 !important;
}

.bg-danger {
  background-color: #dc3545 !important;
}

.bg-secondary {
  background-color: #6c757d !important;
}

.card-body img {
  border-radius: 50%;
  margin-bottom: 15px;
}

/* Responsive Design */
@media (max-width: 768px) {
  .hero-section h1 {
    font-size: 2rem;
  }

  .hero-section .lead {
    font-size: 1rem;
  }

  .sambutan-section .row {
    flex-direction: column-reverse;
  }

  .sambutan-section img {
    width: 100%;
    height: auto;
  }

  .card-title {
    font-size: 1.1rem;
  }

  .card-text {
    font-size: 0.9rem;
  }
}
</style>
