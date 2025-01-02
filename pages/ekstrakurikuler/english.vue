<template>
  <div class="english-club-page">
    <div class="container">
      <h1>English Club</h1>
      <div class="content">
        <!-- Foto -->
        <div class="image-container">
          <img src="~/assets/img/ing.png" alt="English Club" class="english-club-image" />
        </div>

        <!-- Deskripsi -->
        <div class="description-container">
          <h2>Deskripsi Ekstrakurikuler English Club</h2>
          <p>
            Ekstrakurikuler English Club di SMKN 4 Tasikmalaya adalah wadah bagi
            siswa yang memiliki minat untuk mengembangkan kemampuan bahasa Inggris
            mereka. Kegiatan ini bertujuan untuk meningkatkan keterampilan
            berkomunikasi dalam bahasa Inggris, baik secara lisan maupun
            tulisan, melalui berbagai aktivitas yang menyenangkan dan edukatif.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "EnglishClubPage",
};
</script>

<style scoped>
.english-club-page {
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

.english-club-image {
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
