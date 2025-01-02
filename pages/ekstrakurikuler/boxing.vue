<template>
  <div class="boxing-page">
    <div class="container">
      <h1>Ekstrakurikuler Boxing</h1>
      <div class="content">
        <!-- Foto -->
        <div class="image-container">
          <img src="~/assets/img/boxing.png" alt="Boxing" class="boxing-image" />
        </div>

        <!-- Deskripsi -->
        <div class="description-container">
          <h2>Deskripsi Ekstrakurikuler Boxing</h2>
          <p>
            Ekstrakurikuler Boxing di SMKN 4 Tasikmalaya merupakan salah satu program yang bertujuan untuk membentuk
            karakter siswa melalui latihan fisik dan mental yang intens. Boxing bukan hanya mengajarkan teknik bertinju,
            tetapi juga disiplin, keberanian, dan ketahanan dalam menghadapi tantangan. Olahraga tinju ini menjadi
            pilihan
            favorit bagi siswa yang ingin mengasah kemampuan fisik dan mentalnya untuk menghadapi berbagai ujian hidup.
          </p>
          <p>
            Di SMKN 4 Tasikmalaya, ekstrakurikuler Boxing berkembang pesat dan menjadi salah satu cabang olahraga
            unggulan.
            Para anggota yang tergabung dalam ekstrakurikuler ini tidak hanya dilatih untuk menguasai teknik-teknik
            dasar
            tinju, tetapi juga diajarkan untuk mempersiapkan mental dan fisik mereka dalam menghadapi berbagai
            kompetisi,
            baik di tingkat sekolah maupun event olahraga lainnya, seperti pertandingan antarsekolah dan kejuaraan tinju
            tingkat kabupaten.
          </p>
          <p>
            Ekstrakurikuler Boxing di SMKN 4 Tasikmalaya juga bertujuan untuk menanamkan nilai-nilai sportivitas dan
            kerja
            keras, mengajarkan para siswa untuk berjuang dengan semangat juang yang tinggi. Melalui latihan rutin dan
            partisipasi dalam kompetisi, siswa diharapkan dapat mengembangkan potensi terbaik mereka, tidak hanya dalam
            olahraga, tetapi juga dalam kehidupan sehari-hari.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "BoxingPage",
};
</script>

<style scoped>
.boxing-page {
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

.boxing-image {
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
