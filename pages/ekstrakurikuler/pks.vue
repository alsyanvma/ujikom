<template>
  <div class="pks-page">
    <div class="container">
      <h1>Ekstrakurikuler PKS</h1>
      <div class="content">
        <!-- Foto -->
        <div class="image-container">
          <img src="~/assets/img/pks.jpg" alt="PKS" class="pks-image" />
        </div>

        <!-- Deskripsi -->
        <div class="description-container">
          <h2>Deskripsi Ekstrakurikuler PKS</h2>
          <p>
            Ekstrakurikuler PKS (Pendidikan Kewarganegaraan dan Sosial) di SMKN 4 Tasikmalaya bertujuan untuk membekali
            siswa dengan pemahaman yang baik mengenai kehidupan berbangsa dan bernegara. Melalui kegiatan ini, siswa
            diajarkan nilai-nilai luhur dalam kehidupan sosial dan berperan aktif dalam kegiatan kemasyarakatan.
          </p>
          <p>
            Ekstrakurikuler PKS mencakup diskusi, seminar, dan kegiatan sosial yang melibatkan masyarakat sekitar.
            Selain itu, anggota PKS juga dilibatkan dalam berbagai kegiatan yang mendukung terciptanya rasa kepedulian
            sosial dan kedewasaan berpikir bagi para siswa.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "PKSPage",
};
</script>

<style scoped>
.pks-page {
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

.pks-image {
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
