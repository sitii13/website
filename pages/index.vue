<template>
  <!-- Logo Section -->
  <div class="text-center mt-4">
    <img src="~/assets/img/home.jpg" alt="Logo SMKN 4 Tasikmalaya" class="img-fluid" />
  </div>

  <!-- Sambutan Kepala Sekolah Section -->
  <h2 class="bg-secondary text-white text-center py-3 mt-5 mb-4 rounded-3">SAMBUTAN KEPALA SEKOLAH</h2>
  <div class="d-flex align-items-center justify-content-center mt-4 shadow-sm rounded-lg" style="background-color: #f5f5f5; padding: 20px;">
    <img src="~/assets/img/kepsek.png" alt="Kepala Sekolah" class="rounded-circle border border-4 border-primary" style="width: 150px; height: 150px;"/>
    <div class="ms-4">
      <h3 class="text-dark fw-bold">Sambutan Kepala Sekolah</h3>
      <p class="text-muted">Selamat datang di situs resmi SMKN 4 Tasikmalaya. Kami berkomitmen untuk memberikan pendidikan terbaik bagi generasi muda, dengan fokus pada kompetensi di bidang Teknologi dan Komunikasi. Terima kasih telah mengunjungi kami!</p>
      <small class="text-muted">Kepala Sekolah, SMKN 4 Tasikmalaya</small>
    </div>
  </div>

  <!-- Jurusan Section -->
  <div id="jurusan" class="container mt-5">
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
  </div>
</template>

<script>
export default {
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
/* General Card Styles */
.card {
  border-radius: 20px; /* Membuat sudut lebih melengkung */
  transition: transform 0.3s ease-in-out;
  cursor: pointer;
}

.card:hover {
  transform: translateY(-8px); /* Sedikit lebih halus saat hover */
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.15);
}

/* Card Content Styling */
.card-body {
  padding: 25px; /* Menambah padding untuk kesan lebih lega */
}

.card-title {
  font-weight: bold;
  font-size: 1.3rem;
}

.card-text {
  font-size: 1rem;
  line-height: 1.5;
  color: #f1f1f1;
}

/* Background Colors */
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

/* Image Styling */
.card-body img {
  border-radius: 50%; /* Membuat gambar menjadi lingkaran */
  margin-bottom: 15px;
}

/* Spacing */
.container {
  padding-left: 15px;
  padding-right: 15px;
}

/* Responsive Design */
@media (max-width: 768px) {
  .card-title {
    font-size: 1.1rem;
  }

  .card-text {
    font-size: 0.9rem;
  }
}
</style>
