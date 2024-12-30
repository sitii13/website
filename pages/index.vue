<template>
  <!-- Logo Section -->
  <div class="text-center mt-5">
    <img src="~/assets/img/home.jpg" alt="Logo SMKN 4 Tasikmalaya" class="img-fluid rounded" />
  </div>

  <!-- Sambutan Kepala Sekolah Section -->
  <h2 class="text-drak text-center py-4 mt-5 mb-4 rounded-3 shadow-lg">SAMBUTAN KEPALA SEKOLAH</h2>
  <div class="d-flex align-items-center justify-content-center mt-5 shadow-lg p-4 rounded-lg" style="background-color: #f7f7f7;">
    <img src="~/assets/img/kepsek.png" alt="Kepala Sekolah" class="rounded-circle border border-4 border-info" style="width: 160px; height: 160px;" />
    <div class="ms-4">
      <h3 class="text-dark fw-bold">Sambutan Kepala Sekolah</h3>
      <p class="text-muted">Assalamualaikum Warahmatullahi Wabarakatuh
Selamat datang di SMKN 4 Tasikmalaya. Segala puji dan syukur kita panjatkan kehadirat Allah SWT, semoga kita semua ada dalam lindungan-Nya. Dan atas perkenan-Nya pula kami dapat menghadirkan website SMK Negeri 4 Tasikmalaya ini. Kami berharap dengan adanya website di SMK Negeri 4 Tasikmalaya ini para pengunjung dapat mengenal lebih jauh tentang sekolah kami sehingga dapat mempererat tali silaturrahmi antara sekolah dengan masyarakat demi kemajuan kita bersama. Tiada gading yang tak retak, website kami ini masih dalam proses pengembangan, masih banyak kekurangan yang harus kami perbaiki. Kritik dan sarannya yang membangun sangat kami harapkan untuk pengembangan ke depan.
Akhirnya, saya mengucapkan terimakasih yang sebesar-besarnya kepada semua pihak yang tidak dapat disebutkan satu segala bantuan dan persatu atas fasilitasnya yang telah diberikan semoga semua yang kita lakukan bermanfaat bagi masyarakat. Wassalamu'alaikum Warahmatullahi Wabarakatuh.</p>
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
    <div class="row mt-5">
      <!-- Card TKJ -->
      <div class="col-lg-4 col-md-6 mb-5">
        <div class="shadow card h-100 card-hover rounded-3">
          <div class="card-body text-center bg-primary rounded-top">
            <img src="~/assets/img/tkj.png" alt="Logo Sekolah" width="50" height="55" class="me-2" />
            <h5 class="card-title text-white">Teknik Komputer dan Jaringan (TKJ)</h5>
            <p class="card-text text-white">Mahir dalam jaringan komputer dan teknologi informasi. Jurusan ini fokus pada penguasaan konsep dan praktik dalam membangun, mengelola, dan mengamankan jaringan komputer.</p>
            <p class="card-text text-white"><strong>Jumlah Murid: 120</strong></p>
          </div>
        </div>
      </div>

      <!-- Card RPL -->
      <div class="col-lg-4 col-md-6 mb-5">
        <div class="shadow card h-100 card-hover rounded-3">
          <div class="card-body text-center bg-success rounded-top">
            <img src="~/assets/img/rpl.png" alt="Logo Sekolah" width="50" height="55" class="me-2" />
            <h5 class="card-title text-white">Rekayasa Perangkat Lunak (RPL)</h5>
            <p class="card-text text-white">Ahli dalam pengembangan perangkat lunak modern. Jurusan ini mempelajari cara merancang, mengembangkan, dan memelihara perangkat lunak, termasuk aplikasi berbasis desktop, web, dan mobile.</p>
            <p class="card-text text-white"><strong>Jumlah Murid: 100</strong></p>
          </div>
        </div>
      </div>

      <!-- Card DKV -->
      <div class="col-lg-4 col-md-6 mb-5">
        <div class="shadow card h-100 card-hover rounded-3">
          <div class="card-body text-center bg-warning rounded-top">
            <img src="~/assets/img/dkv.png" alt="Logo Sekolah" width="50" height="55" class="me-2" />
            <h5 class="card-title text-dark">Desain Komunikasi Visual (DKV)</h5>
            <p class="card-text text-dark">Kreatif dalam seni desain dan komunikasi visual. Jurusan ini mengajarkan seni dan teknik dalam menciptakan desain visual yang komunikatif dan menarik.</p>
            <p class="card-text text-dark"><strong>Jumlah Murid: 90</strong></p>
          </div>
        </div>
      </div>

      <!-- Card TBSM -->
      <div class="col-lg-6 col-md-6 mb-5">
        <div class="shadow card h-100 card-hover rounded-3">
          <div class="card-body text-center bg-danger rounded-top">
            <img src="~/assets/img/tsm.png" alt="Logo Sekolah" width="50" height="55" class="me-2" />
            <h5 class="card-title text-white">Teknik Bisnis Sepeda Motor (TBSM)</h5>
            <p class="card-text text-white">Ahli dalam perbaikan dan manajemen bisnis sepeda motor. Jurusan ini mempelajari teknik perawatan, perbaikan, dan modifikasi sepeda motor, sekaligus menanamkan keterampilan kewirausahaan.</p>
            <p class="card-text text-white"><strong>Jumlah Murid: 80</strong></p>
          </div>
        </div>
      </div>

      <!-- Card TOI -->
      <div class="col-lg-6 col-md-6 mb-5">
        <div class="shadow card h-100 card-hover rounded-3">
          <div class="card-body text-center bg-secondary rounded-top">
            <img src="~/assets/img/toi.png" alt="Logo Sekolah" width="50" height="55" class="me-2" />
            <h5 class="card-title text-white">Teknik Otomasi Industri (TOI)</h5>
            <p class="card-text text-white">Mahir dalam sistem otomatisasi dan teknologi industri. Jurusan ini berfokus pada teknologi otomotif yang diterapkan dalam skala industri.</p>
            <p class="card-text text-white"><strong>Jumlah Murid: 70</strong></p>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Berita Section -->
  <div id="berita" class="container mt-5">
    <div class="row">
      <div class="col text-center">
        <h2 class="fw-bold">Berita Terbaru</h2>
        <p class="text-muted">"Berita terbaru seputar kegiatan dan informasi penting SMKN 4 Tasikmalaya."</p>
      </div>
    </div>

    <!-- Row Berita Cards -->
    <div class="row mt-5">
      <div class="col-lg-4 col-md-6 mb-5">
        <div class="shadow card h-100 card-hover rounded-3">
          <img src="~/assets/img/13.jpeg" alt="Berita 1" class="card-img-top rounded-3" />
          <div class="card-body">
            <h5 class="card-title">Pelatihan Teknologi Jaringan</h5>
            <p class="card-text">SMKN 4 Tasikmalaya mengadakan pelatihan teknologi jaringan untuk siswa jurusan TKJ. Acara ini dihadiri oleh pakar di bidangnya dan bertujuan untuk meningkatkan keterampilan siswa dalam jaringan komputer.</p>
          </div>
        </div>
      </div>

      <div class="col-lg-4 col-md-6 mb-5">
        <div class="shadow card h-100 card-hover rounded-3">
          <img src="~/assets/img/12.jpeg" alt="Berita 2" class="card-img-top rounded-3" />
          <div class="card-body">
            <h5 class="card-title">Workshop Desain Komunikasi Visual</h5>
            <p class="card-text">Jurusan DKV mengadakan workshop untuk siswa dalam pembuatan desain komunikasi visual. Para siswa belajar langsung dengan ahli desain untuk menciptakan karya kreatif dan inovatif.</p>
          </div>
        </div>
      </div>

      <div class="col-lg-4 col-md-6 mb-5">
        <div class="shadow card h-100 card-hover rounded-3">
          <img src="~/assets/img/14.jpeg" alt="Berita 3" class="card-img-top rounded-3" />
          <div class="card-body">
            <h5 class="card-title">Pencapaian Siswa RPL di Lomba Nasional</h5>
            <p class="card-text">Siswa jurusan RPL berhasil meraih juara pertama dalam lomba pengembangan perangkat lunak tingkat nasional. Prestasi ini membanggakan sekolah dan menjadi inspirasi bagi siswa lainnya.</p>
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
      berita: [
        { title: "Pelatihan Teknologi Jaringan", description: "SMKN 4 Tasikmalaya mengadakan pelatihan teknologi jaringan untuk siswa jurusan TKJ.", image: "~/assets/img/berita1.jpg" },
        { title: "Workshop Desain Komunikasi Visual", description: "Jurusan DKV mengadakan workshop untuk siswa dalam pembuatan desain komunikasi visual.", image: "~/assets/img/berita2.jpg" },
        { title: "Pencapaian Siswa RPL di Lomba Nasional", description: "Siswa jurusan RPL berhasil meraih juara pertama dalam lomba pengembangan perangkat lunak tingkat nasional.", image: "~/assets/img/berita3.jpg" }
      ]
    };
  }
};
</script>

<style scoped>
/* General Card Styles */
.card {
  border-radius: 20px;
  transition: transform 0.3s ease-in-out;
  cursor: pointer;
}

.card:hover {
  transform: translateY(-8px);
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
}

/* Card Content Styling */
.card-body {
  padding: 25px;
}

.card-title {
  font-weight: bold;
  font-size: 1.4rem;
}

.card-text {
  font-size: 1rem;
  line-height: 1.6;
  color: #333;
}

.card-img-top {
  height: 200px;
  object-fit: cover;
  border-radius: 15px;
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

/* Spacing */
.container {
  padding-left: 15px;
  padding-right: 15px;
}

/* Responsive Design */
@media (max-width: 768px) {
  .card-title {
    font-size: 1.2rem;
  }

  .card-text {
    font-size: 0.95rem;
  }
}
</style>
