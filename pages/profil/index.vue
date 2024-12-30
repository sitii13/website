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
  </div>
</template>

<script>
  export default {
    name: 'ProfilPage',
  }
</script>

<style scoped>
  h2, h3, h4 {
    margin-bottom: 20px;
    color: #2c3e50;
  }

  table {
    width: 100%;
    border-collapse: collapse;
  }

  th, td {
    text-align: left;
    vertical-align: middle;
    padding: 12px;
  }

  th {
    width: 25%;
    background-color: #f8f9fa;
    font-weight: bold;
    color: #495057;
  }

  td {
    background-color: #ffffff;
  }

  table tbody tr:hover {
    background-color: #f1f1f1;
  }

  .container {
    background-color: #f4f6f9;
    padding: 30px;
    border-radius: 8px;
  }

  .d-flex {
    gap: 20px;
  }

  .p-2 {
    padding: 10px;
  }

  .shadow-sm {
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
  }

  .img-fluid {
    max-width: 100%;
    height: auto;
  }

  .text-center {
    display: flex;
    justify-content: center;
    align-items: center;
    max-width: 200px;
    margin: 0 auto;
  }

  .logo-container img {
    max-width: 150px;
    height: auto;
  }

  /* Responsiveness */
  @media (max-width: 768px) {
    .d-flex {
      flex-direction: column;
      align-items: center;
    }

    .p-2 {
      width: 100%;
    }

    h2 {
      font-size: 1.5rem;
    }

    .logo-container img {
      max-width: 120px;
    }
  }
</style>
