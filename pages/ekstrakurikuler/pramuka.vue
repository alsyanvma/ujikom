<template>
  <div class="pramuka-page">
    <div class="container">
      <h1>Ekstrakurikuler Pramuka</h1>
      <div class="content">
        <!-- Foto -->
        <div class="image-container">
          <img src="~/assets/img/pramuka.jpeg" alt="Pramuka" class="pramuka-image" />
        </div>

        <!-- Deskripsi -->
        <div class="description-container">
          <h2>Deskripsi Ekstrakurikuler Pramuka</h2>
          <p>
            Ekstrakurikuler Pramuka di SMKN 4 Tasikmalaya adalah wadah bagi siswa untuk mengembangkan diri melalui
            kegiatan yang berorientasi pada pendidikan karakter, kepemimpinan, dan kebersamaan. Kegiatan ini bertujuan
            untuk memperkuat rasa disiplin, tanggung jawab, serta menumbuhkan semangat kerjasama dalam kegiatan alam
            bebas dan kemasyarakatan.
          </p>
          <p>
            Setiap tahunnya, ekstrakurikuler ini rutin mengadakan berbagai kegiatan, seperti perkemahan, latihan dasar
            kepemimpinan, serta berbagai kompetisi yang melibatkan keterampilan di alam terbuka. Selain itu, kegiatan
            ini juga mengajarkan nilai-nilai keberanian, solidaritas, dan cinta tanah air melalui kegiatan-kegiatan yang
            bermanfaat.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "PramukaPage",
};
</script>

<style scoped>
.pramuka-page {
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

.pramuka-image {
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
