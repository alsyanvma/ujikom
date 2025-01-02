<template>
  <div class="art-page">
    <div class="container">
      <h1>Ekstrakurikuler Seni</h1>
      <div class="content">
        <!-- Foto -->
        <div class="image-container">
          <img src="~/assets/img/musik.jpg" alt="Art" class="art-image" />
        </div>

        <!-- Deskripsi -->
        <div class="description-container">
          <h2>Deskripsi Ekstrakurikuler Seni</h2>
          <p>
            Ekstrakurikuler Seni di SMKN 4 Tasikmalaya merupakan wadah bagi siswa yang memiliki minat dan bakat dalam
            dunia seni, baik itu seni musik, tari, atau seni lainnya. Kegiatan ini bertujuan untuk
            mengembangkan kreativitas, memperkaya pengetahuan seni, serta meningkatkan apresiasi terhadap berbagai
            bentuk seni.
          </p>
          <p>
            Setiap tahunnya, ekstrakurikuler ini menyelenggarakan berbagai kegiatan seperti pertunjukan seni, pameran
            lukisan, serta pelatihan seni musik dan tari. Kami juga berpartisipasi dalam berbagai kompetisi seni, baik
            tingkat sekolah, daerah, maupun nasional.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ArtPage",
};
</script>

<style scoped>
.art-page {
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

.art-image {
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
