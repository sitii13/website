<template>
  <div class="gallery-container">
    <h1>Galeri Sekolah</h1>
    <div class="row">
      <!-- Kegiatan 1 -->
      <div class="col-lg-4 col-md-6 col-sm-12 mb-4">
        <div class="card shadow-lg rounded-3">
          <img src="/assets/img/binsik.jpg" alt="Kegiatan 1" class="card-img-top" />
        </div>
      </div>

      <!-- Kegiatan 2 -->
      <div class="col-lg-4 col-md-6 col-sm-12 mb-4">
        <div class="card shadow-lg rounded-3">
          <img src="/assets/img/hari_guru.jpg" alt="Kegiatan 2" class="card-img-top" />
        </div>
      </div>

      <!-- Kegiatan 3 -->
      <div class="col-lg-4 col-md-6 col-sm-12 mb-4">
        <div class="card shadow-lg rounded-3">
          <img src="/assets/img/doa.jpg" alt="Kegiatan 3" class="card-img-top" />
        </div>
      </div>

      <!-- Kegiatan 4 -->
      <div class="col-lg-4 col-md-6 col-sm-12 mb-4">
        <div class="card shadow-lg rounded-3">
          <img src="/assets/img/expo.webp" alt="Kegiatan 4" class="card-img-top" />
        </div>
      </div>

      <!-- Kegiatan 5 -->
      <div class="col-lg-4 col-md-6 col-sm-12 mb-4">
        <div class="card shadow-lg rounded-3">
          <img src="/assets/img/1.png" alt="Kegiatan 5" class="card-img-top" />
        </div>
      </div>

      <!-- Kegiatan 6 -->
      <div class="col-lg-4 col-md-6 col-sm-12 mb-4">
        <div class="card shadow-lg rounded-3">
          <img src="/assets/img/fair.jpg" alt="Kegiatan 6" class="card-img-top" />
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.gallery-container {
  padding: 40px;
  text-align: center;
  background-color: #f1f5f8;
}

h1 {
  margin-bottom: 30px;
  font-size: 2.5rem;
  font-weight: bold;
  color: #343a40;
  letter-spacing: 1px;
}

.card-img-top {
  height: 250px;
  object-fit: cover;
  width: 100%;
  border-radius: 8px;
  transition: transform 0.4s ease-in-out, box-shadow 0.3s ease-in-out;
}

.card-img-top:hover {
  transform: scale(1.1);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
}

.card-body {
  padding: 15px;
}

.card {
  display: flex;
  flex-direction: column;
  height: 100%;
  border-radius: 10px;
  overflow: hidden;
  transition: box-shadow 0.3s ease-in-out;
}

.card:hover {
  box-shadow: 0 12px 20px rgba(0, 0, 0, 0.1);
}

.card-text {
  font-size: 1rem;
  color: #555;
}

@media (max-width: 992px) {
  .col-lg-4 {
    margin-bottom: 20px;
  }
}

@media (max-width: 768px) {
  .col-md-6 {
    margin-bottom: 20px;
  }
}
</style>
