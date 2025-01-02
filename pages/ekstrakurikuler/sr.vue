<template>
  <div class="safety-riding-page">
    <div class="container">
      <h1>Ekstrakurikuler Safety Riding</h1>
      <div class="content">
        <!-- Foto -->
        <div class="image-container">
          <img src="~/assets/img/sr.jpg" alt="Safety Riding" class="safety-riding-image" />
        </div>

        <!-- Deskripsi -->
        <div class="description-container">
          <h2>Deskripsi Ekstrakurikuler Safety Riding</h2>
          <p>
            Ekstrakurikuler Safety Riding di SMKN 4 Tasikmalaya bertujuan untuk mengedukasi dan melatih siswa mengenai
            keselamatan berkendara, baik di jalan raya maupun dalam kehidupan sehari-hari. Kegiatan ini mencakup
            pengetahuan tentang peraturan lalu lintas, teknik berkendara yang aman, serta pentingnya perlengkapan
            keselamatan seperti helm dan pelindung lainnya.
          </p>
          <p>
            Setiap tahunnya, ekstrakurikuler ini mengadakan pelatihan dan simulasi berkendara yang melibatkan berbagai
            pihak, serta mengikuti kompetisi safety riding yang diselenggarakan oleh berbagai organisasi. Selain itu,
            kami juga sering mengadakan kampanye keselamatan lalu lintas untuk meningkatkan kesadaran di kalangan siswa.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SafetyRidingPage",
};
</script>

<style scoped>
.safety-riding-page {
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

.safety-riding-image {
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
