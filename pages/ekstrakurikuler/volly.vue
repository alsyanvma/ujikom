<template>
  <div class="volly-page">
    <div class="container">
      <h1>Ekstrakurikuler Volly</h1>
      <div class="content">
        <!-- Foto -->
        <div class="image-container">
          <img src="~/assets/img/volly.jpg" alt="Volly" class="volly-image" />
        </div>

        <!-- Deskripsi -->
        <div class="description-container">
          <h2>Deskripsi Ekstrakurikuler Volly</h2>
          <p>
            Ekstrakurikuler Volly di SMKN 4 Tasikmalaya merupakan tempat bagi siswa yang memiliki minat dan bakat dalam
            olahraga bola voli. Kegiatan ini bertujuan untuk meningkatkan keterampilan bermain bola voli, mempererat
            kekompakan tim, serta membentuk karakter kepemimpinan dan sportivitas di antara siswa.
          </p>
          <p>
            Setiap tahunnya, ekstrakurikuler ini mengadakan latihan rutin, kompetisi antar kelas, serta pertandingan
            persahabatan dengan sekolah-sekolah lain. Kami juga berpartisipasi dalam berbagai turnamen bola voli yang
            diadakan oleh berbagai pihak.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "VollyPage",
};
</script>

<style scoped>
.volly-page {
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

.volly-image {
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
