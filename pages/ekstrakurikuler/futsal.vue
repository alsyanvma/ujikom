<template>
  <div class="futsal-page">
    <div class="container">
      <h1>Ekstrakurikuler Futsal</h1>
      <div class="content">
        <!-- Foto -->
        <div class="image-container">
          <img src="~/assets/img/futsal.png" alt="Futsal" class="futsal-image" />
        </div>

        <!-- Deskripsi -->
        <div class="description-container">
          <h2>Deskripsi Ekstrakurikuler Futsal</h2>
          <p>
            Ekstrakurikuler Futsal di SMKN 4 Tasikmalaya merupakan wadah bagi siswa yang memiliki minat dan bakat dalam
            olahraga futsal. Kegiatan ini bertujuan untuk meningkatkan keterampilan bermain futsal, mempererat
            kekompakan tim, serta membentuk karakter kepemimpinan dan sportivitas di antara siswa.
          </p>
          <p>
            Setiap tahunnya, ekstrakurikuler ini rutin mengadakan latihan, kompetisi antar kelas, serta pertandingan
            persahabatan dengan sekolah-sekolah lain. Selain itu, kami juga mengikuti beberapa turnamen futsal yang
            diadakan oleh berbagai pihak, baik di tingkat lokal maupun nasional.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FutsalPage",
};
</script>

<style scoped>
.futsal-page {
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

.futsal-image {
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
