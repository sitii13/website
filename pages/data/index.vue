<template>
  <div>
    <!-- Konten Data -->
    <div id="data" class="container mt-5">
      <div class="row">
        <div class="col text-center">
          <h2 class="display-4 text-drak font-weight-bold">Data Sekolah</h2>
          <p class="lead text-muted">Informasi jumlah guru, staf, dan murid di SMKN 4 Tasikmalaya.</p>
        </div>
      </div>

      <!-- Tabel Jumlah Guru, Staf, dan Pegawai -->
      <div class="row mt-4">
        <div class="col-lg-6 mb-4">
          <h3 class="text-drak">Jumlah Guru dan Staf</h3>
          <table class="table table-striped table-hover shadow-lg rounded">
            <thead class="thead-dark">
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

      <!-- Tabel Jumlah Murid Per Jurusan -->
      <div class="row mt-4">
        <div class="col">
          <h3 class="text-drak">Jumlah Murid Per Jurusan</h3>
          <table class="table table-bordered table-striped table-hover shadow-lg rounded">
            <thead class="thead-dark">
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

table {
  border-collapse: collapse;
}

thead {
  background-color: #343a40;
  color: white;
}

th, td {
  padding: 10px;
  text-align: center;
}

.table-hover tbody tr:hover {
  background-color: #f8f9fa;
}

.shadow-lg {
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
}

.rounded {
  border-radius: 8px;
}

.text-muted {
  color: #6c757d;
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
</style>
