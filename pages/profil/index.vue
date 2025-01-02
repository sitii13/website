<template>
  <div class="container mt-4">
    <!-- Konten Profil Sekolah -->
    <div class="d-flex align-items-center flex-wrap mb-4">
      <!-- Kolom Tabel Informasi -->
      <div class="p-2 flex-fill">
        <h2>Informasi Sekolah</h2>
        <table class="table table-bordered shadow-sm">
          <tbody>
            <tr>
              <th scope="row">Nama Sekolah</th>
              <td>SMKN 4 Tasikmalaya</td>
            </tr>
            <tr>
              <th scope="row">Tahun Berdiri</th>
              <td>2012</td>
            </tr>
            <tr>
              <th scope="row">Alamat</th>
              <td>Jl Depok Kel. Sukamenak Kec. Purbaratu Kota Tasikmalaya 46196.</td>
            </tr>
            <tr>
              <th scope="row">Nomor Statistik Sekolah</th>
              <td>401327810004</td>
            </tr>
          </tbody>
        </table>
      </div>

      <!-- Kolom Gambar Logo -->
      <div class="p-2 flex-fill text-center logo-container">
        <img
          src="~/assets/img/logo.png"
          alt="Logo SMKN 4 Tasikmalaya"
          class="img-fluid rounded shadow"
        />
      </div>
    </div>

    <!-- Visi Section -->
    <div class="row mt-5">
      <div class="col-md-6 mb-4">
        <div class="card shadow-lg rounded">
          <div class="card-body">
            <h3 class="card-title text-dark">Visi</h3>
            <p class="card-text">
              Menjadi sekolah yang unggul dalam bidang teknologi informasi dan komunikasi serta menghasilkan lulusan yang siap bersaing di dunia kerja dan siap melanjutkan ke pendidikan lebih tinggi.
            </p>
          </div>
        </div>
      </div>

      <!-- Misi Section -->
      <div class="col-md-6 mb-4">
        <div class="card shadow-lg rounded">
          <div class="card-body">
            <h3 class="card-title text-dark">Misi</h3>
            <ul>
              <li>Menyelenggarakan pendidikan yang berkualitas di bidang teknologi informasi dan komunikasi.</li>
              <li>Membangun keterampilan dan karakter siswa untuk siap bekerja dan berinovasi.</li>
              <li>Menjalin kerjasama dengan industri dan dunia kerja untuk meningkatkan kualitas pendidikan.</li>
              <li>Mengembangkan sarana dan prasarana pendidikan yang mendukung proses pembelajaran yang efektif.</li>
            </ul>
          </div>
        </div>
      </div>
    </div>

    <!-- Sejarah Sekolah -->
    <h3>Sejarah</h3>
    <p>
      Sejalan dengan Program Pemerintah dibidang pendidikan Menengah Kejuruan pada saat itu yakni pemerataan akses ditambah
      pula dengan banyaknya keinginan masyarakat yang mengharapkan adanya SMK Negeri di daerah Kecamatan Purbaratu Kota
      Tasikmalaya, terutama untuk menampung tamatan dari SLTP yang ingin melanjutkan ke SMK maka beberapa tokoh masyarakat,
      unsur pejabat pemerintah di Kecamatan Purbaratu Kota Tasikmalaya mengusulkan kepada pemerintah Kota Tasikmalaya dan
      Pemerintah Provinsi Jawa Barat, agar berdirinya SMK Negeri di Kecamatan Purbaratu Kota Tasikmalaya.
      Setelah melalui perjuangan yang sangat panjang dari berbagai pihak khususnya Disdik Kota Tasikmalaya dan
      pihak-pihak terkait lainnya sesuai prosedur dan ketentuan yang berlaku pada waktu itu dengan mengucapkan syukur
      Alhamdulillah akhirnya pada tahun pelajaran 2010/2011 SMK Negeri 4 Tasikmalaya mulai berdiri, pada awalnya membuka
      Kompetensi Keahlian Teknik Komputer dan Jaringan dengan pendaftar peserta Didik Baru pada waktu itu berjumlah 44 orang.
      Pada awalnya tempat belajar menumpang di SMP Negeri 17 Kota Tasikmalaya, dan sekolah induknya adalah SMK Negeri 2 Kota
      Tasikmalaya, Untuk Tenaga pendidik dan Tenaga Kependidikan masih dibantu sepenuhnya oleh kedua sekolah tersebut.
      Pada tahun 2012 keluarlah surat Izin Pendirian berdasarkan keputusan kepala Badan Pelayanan Perizinan Terpadu Kota
      Tasikmalaya No. 420/9/SK-BPPT/2012 Tanggal 06 Februari 2012.
    </p>

    <!-- Konten Data -->
    <div id="data" class="container mt-5">
      <div class="row">
        <div class="col text-center">
          <h2 class="display-4 font-weight-bold text-dark">Data Sekolah</h2>
          <p class="lead text-muted">Informasi jumlah guru, staf, dan murid di SMKN 4 Tasikmalaya.</p>
        </div>
      </div>

      <!-- Card untuk Jumlah Guru, Staf, dan Pegawai -->
      <div class="row mt-4">
        <div class="col-lg-6 mb-4">
          <div class="card shadow-lg rounded">
            <div class="card-body">
              <h3 class="card-title text-dark">Jumlah Guru dan Staf</h3>
              <table class="table table-bordered table-hover">
                <thead class="thead-light">
                  <tr>
                    <th>Kategori</th>
                    <th>Jumlah</th>
                  </tr>
                </thead>
                <tbody>
                  <tr>
                    <td>Guru</td>
                    <td>{{ jumlahGuru }}</td>
                  </tr>
                  <tr>
                    <td>Staf Administrasi</td>
                    <td>{{ jumlahStafAdministrasi }}</td>
                  </tr>
                  <tr>
                    <td>Pegawai Lainnya</td>
                    <td>{{ jumlahPegawaiLainnya }}</td>
                  </tr>
                </tbody>
              </table>
            </div>
          </div>
        </div>
      </div>

      <!-- Card untuk Jumlah Murid Per Jurusan -->
      <div class="row mt-4">
        <div class="col">
          <div class="card shadow-lg rounded">
            <div class="card-body">
              <h3 class="card-title text-dark">Jumlah Murid Per Jurusan</h3>
              <table class="table table-bordered table-striped table-hover">
                <thead class="thead-light">
                  <tr>
                    <th>Jurusan</th>
                    <th>Jumlah Murid</th>
                  </tr>
                </thead>
                <tbody>
                  <tr v-for="(jumlah, jurusan) in jumlahMuridPerJurusan" :key="jurusan">
                    <td>{{ jurusan }}</td>
                    <td>{{ jumlah }}</td>
                  </tr>
                </tbody>
              </table>
            </div>
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
      // Data jumlah guru, staf, dan pegawai
      jumlahGuru: 50,
      jumlahStafAdministrasi: 15,
      jumlahPegawaiLainnya: 10,

      // Data jumlah murid per jurusan
      jumlahMuridPerJurusan: {
        "TEKNIK KOMPUTER JARINGAN": 120,
        "REKAYASA PERANGKAT LUNAK": 100,
        "TEKNIK BISNIS DAN SEPEDA MOTOR": 80,
        "TEKNIK OTOMASI INDUSTRI": 90,
        "DESAIN KOMUNIKASI VISUAL": 70
      }
    };
  }
};
</script>

<style scoped>
/* Menambahkan beberapa styling untuk mempercantik tampilan */
.container {
  font-family: 'Roboto', sans-serif;
}

h2 {
  font-weight: 700;
}

.card {
  background-color: #ffffff;
}

.card-body {
  padding: 1.5rem;
}

table {
  border-collapse: collapse;
}

thead {
  background-color: #f1f1f1;
  color: #343a40;
}

th, td {
  padding: 12px;
  text-align: center;
  font-size: 1rem;
}

.table-hover tbody tr:hover {
  background-color: #e9ecef;
}

.shadow-lg {
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
}

.rounded {
  border-radius: 10px;
}

.text-muted {
  color: #6c757d;
}

.text-dark {
  color: #343a40;
}

.text-success {
  color: #28a745;
}

.text-info {
  color: #17a2b8;
}

.lead {
  font-size: 1.25rem;
  font-weight: 300;
}

.card-title {
  font-size: 1.5rem;
  font-weight: 500;
}

.table-striped tbody tr:nth-child(odd) {
  background-color: #f8f9fa;
}
</style>
