<template>
  <div>
    <header class="header">
      <h1>Ekstrakurikuler</h1>
      <p>Sekolah kami memiliki beberapa Ekstrakurikuler yang tersedia:</p>
    </header>
    <main class="grid-container">
      <div v-for="ekskul in ekstrakurikuler" :key="ekskul.id" class="card">
        <img :src="ekskul.image" :alt="ekskul.name + ' logo'" />
        <h2>{{ ekskul.name }}</h2>
        <p>{{ ekskul.description }}</p>
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: "Ekstrakurikuler",
  data() {
    return {
      ekstrakurikuler: [
        {
          id: 1,
          name: "English Club",
          description:
            "Melatih kemampuan berbahasa Inggris melalui diskusi, debat, dan kegiatan interaktif lainnya.",
          image: "path/to/inggris.jpeg",
        },
        {
          id: 2,
          name: "IT Club",
          description:
            "Mengembangkan keterampilan teknologi, termasuk pemrograman, desain grafis, dan lainnya.",
          image: "assets/img/it.jpeg",
        },
        {
          id: 3,
          name: "Bulu Tangkis",
          description:
            "Meningkatkan kemampuan bermain bulu tangkis sambil menjaga kesehatan.",
          image: "assets/img/badminton.jpeg",
        },
        // Tambahkan lebih banyak data jika diperlukan
      ],
    };
  },
};
</script>

<style scoped>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f9f9f9;
}

.header {
  text-align: center;
  padding: 20px;
  background-color: #003366; /* Biru utama */
  color: white;
}

.grid-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px;
  padding: 20px;
}

.card {
  background: white;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  overflow: hidden;
  text-align: center;
  padding: 20px;
}

.card img {
  max-width: 100px;
  margin-bottom: 15px;
}

.card h2 {
  color: #003366;
  margin-bottom: 10px;
}

.card p {
  font-size: 14px;
  color: #666;
}
</style>