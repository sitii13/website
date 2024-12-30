<template>
  <div>
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
