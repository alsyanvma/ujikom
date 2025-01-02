<template>
  <div class="football-page">
    <div class="container">
      <h1>Ekstrakurikuler Sepak Bola</h1>
      <div class="content">
        <!-- Foto -->
        <div class="image-container">
          <img src="~/assets/img/sb.jpg" alt="Football" class="football-image" />
        </div>

        <!-- Deskripsi -->
        <div class="description-container">
          <h2>Deskripsi Ekstrakurikuler Sepak Bola</h2>
          <p>
            Ekstrakurikuler Sepak Bola di SMKN 4 Tasikmalaya adalah tempat yang tepat bagi siswa yang memiliki minat dan
            bakat dalam dunia sepak bola. Kegiatan ini bertujuan untuk meningkatkan keterampilan bermain sepak bola,
            membentuk kerjasama tim yang solid, serta menumbuhkan karakter kepemimpinan, sportivitas, dan kedisiplinan
            di kalangan siswa.
          </p>
          <p>
            Setiap tahunnya, ekstrakurikuler ini secara rutin mengadakan latihan, kompetisi antar kelas, serta
            pertandingan persahabatan dengan sekolah-sekolah lain. Selain itu, kami juga turut berpartisipasi dalam
            beberapa turnamen sepak bola yang diselenggarakan oleh berbagai pihak.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FootballPage",
};
</script>

<style scoped>
.football-page {
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

.football-image {
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
