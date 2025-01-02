<template>
  <div class="perisai-diri-page">
    <div class="container">
      <h1>Ekstrakurikuler Perisai Diri</h1>
      <div class="content">
        <!-- Foto -->
        <div class="image-container">
          <img src="~/assets/img/pd.jpg" alt="Perisai Diri" class="perisai-diri-image" />
        </div>

        <!-- Deskripsi -->
        <div class="description-container">
          <h2>Deskripsi Ekstrakurikuler Perisai Diri</h2>
          <p>
            Ekstrakurikuler Perisai Diri di SMKN 4 Tasikmalaya adalah wadah bagi siswa yang ingin mengembangkan
            keterampilan bela diri dan menjaga kesehatan tubuh. Perisai Diri mengajarkan seni bela diri yang bertujuan
            untuk membentuk fisik yang kuat, mental yang tangguh, serta meningkatkan rasa percaya diri.
          </p>
          <p>
            Kegiatan dalam ekstrakurikuler ini mencakup latihan rutin gerakan bela diri, pengenalan teknik dasar, dan
            aplikasi bela diri dalam situasi nyata. Selain itu, anggota Perisai Diri juga mengikuti berbagai ajang
            kompetisi bela diri, baik di tingkat sekolah maupun di luar sekolah.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "PerisaiDiriPage",
};
</script>

<style scoped>
.perisai-diri-page {
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

.perisai-diri-image {
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
