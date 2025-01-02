<template>
  <div class="pencak-silat-page">
    <div class="container">
      <h1>Ekstrakurikuler Pencak Silat</h1>
      <div class="content">
        <!-- Foto -->
        <div class="image-container">
          <img src="~/assets/img/s.png" alt="Pencak Silat" class="pencak-silat-image" />
        </div>

        <!-- Deskripsi -->
        <div class="description-container">
          <h2>Deskripsi Ekstrakurikuler Pencak Silat</h2>
          <p>
            Ekstrakurikuler Pencak Silat di SMKN 4 Tasikmalaya merupakan wadah bagi siswa yang memiliki minat dan bakat
            dalam seni bela diri tradisional Pencak Silat. Kegiatan ini bertujuan untuk meningkatkan keterampilan dalam
            bela diri, mempererat kekompakan tim, serta membentuk karakter disiplin, keberanian, dan sportivitas di
            antara siswa.
          </p>
          <p>
            Setiap tahunnya, ekstrakurikuler ini rutin mengadakan latihan intensif, kompetisi antar kelas, serta
            pertandingan persahabatan dengan sekolah-sekolah lain. Kami juga mengikuti berbagai turnamen pencak silat
            yang diadakan oleh berbagai pihak, baik di tingkat daerah maupun nasional.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "PencakSilatPage",
};
</script>

<style scoped>
.pencak-silat-page {
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

.pencak-silat-image {
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
