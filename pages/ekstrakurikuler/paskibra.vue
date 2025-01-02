<template>
  <div class="paskibra-page">
    <div class="container">
      <h1>Ekstrakurikuler Paskibra</h1>
      <div class="content">
        <!-- Foto -->
        <div class="image-container">
          <img src="~/assets/img/pas.jpg" alt="Paskibra" class="paskibra-image" />
        </div>

        <!-- Deskripsi -->
        <div class="description-container">
          <h2>Deskripsi Ekstrakurikuler Paskibra</h2>
          <p>
            Ekstrakurikuler Paskibra di SMKN 4 Tasikmalaya merupakan wadah bagi siswa yang memiliki minat dalam
            baris-berbaris, peraturan, dan upacara. Kegiatan ini bertujuan untuk membentuk kedisiplinan, kekompakan,
            serta rasa tanggung jawab yang tinggi pada setiap anggotanya.
          </p>
          <p>
            Setiap tahunnya, ekstrakurikuler ini rutin mengadakan latihan rutin, persiapan upacara bendera, serta
            kegiatan sosial yang melibatkan siswa dalam berbagai acara sekolah. Selain itu, anggota Paskibra juga
            berpartisipasi dalam berbagai lomba baris-berbaris yang diadakan oleh berbagai pihak.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "PaskibraPage",
};
</script>

<style scoped>
.paskibra-page {
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

.paskibra-image {
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
