<template>
  <div class="cinema-page">
    <div class="container">
      <h1>Cinema</h1>
      <div class="content">
        <!-- Foto -->
        <div class="image-container">
          <img src="~/assets/img/cinema.png" alt="Cinema" class="cinema-image" />
        </div>

        <!-- Deskripsi -->
        <div class="description-container">
          <h2>Deskripsi Ekstrakurikuler Cinema</h2>
          <p>
            Ekstrakurikuler Cinema di SMKN 4 Tasikmalaya adalah wadah bagi siswa
            yang memiliki minat dan bakat dalam dunia perfilman. Kegiatan ini
            bertujuan untuk mengembangkan keterampilan dalam pembuatan film,
            pengoperasian kamera, editing video.
          </p>
          <p>
            Setiap tahun, ekstrakurikuler ini menyelenggarakan berbagai kegiatan,
            mulai dari pelatihan dasar perfilman, pembuatan film pendek.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "CinemaPage",
};
</script>

<style scoped>
.cinema-page {
  padding: 20px;
}

h1 {
  text-align: center;
  font-size: 2.5rem;
  margin-bottom: 30px;
  color: #333;
}

.content {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.image-container {
  text-align: center;
  margin-bottom: 20px;
}

.cinema-image {
  width: 100%;
  max-width: 800px;
  height: auto;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.description-container {
  max-width: 800px;
  text-align: justify;
  margin-top: 20px;
}

.description-container h2 {
  font-size: 1.8rem;
  color: #007bff;
}

.description-container p {
  font-size: 1.1rem;
  line-height: 1.6;
  color: #555;
}
</style>
