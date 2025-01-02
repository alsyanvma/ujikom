<template>
  <div class="plh-page">
    <div class="container">
      <h1>Ekstrakurikuler Pencinta Lingkungan Hidup</h1>
      <div class="content">
        <!-- Foto -->
        <div class="image-container">
          <img src="~/assets/img/plh.png" alt="Pencinta Lingkungan Hidup" class="plh-image" />
        </div>

        <!-- Deskripsi -->
        <div class="description-container">
          <h2>Deskripsi Ekstrakurikuler Pencinta Lingkungan Hidup</h2>
          <p>
            Ekstrakurikuler Pencinta Lingkungan Hidup di SMKN 4 Tasikmalaya bertujuan untuk menumbuhkan rasa peduli dan
            tanggung jawab siswa terhadap kelestarian alam dan lingkungan sekitar. Kegiatan ini melibatkan berbagai
            program yang berfokus pada pelestarian alam, pengelolaan sampah, penanaman pohon, dan berbagai aktivitas
            sosial yang mendukung keberlanjutan lingkungan.
          </p>
          <p>
            Setiap tahunnya, ekstrakurikuler ini mengadakan berbagai kegiatan seperti kampanye lingkungan, kerja bakti,
            serta kegiatan edukasi mengenai cara hidup ramah lingkungan. Para anggota juga aktif dalam merancang dan
            mengimplementasikan solusi untuk menjaga kebersihan dan kelestarian alam.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "PLHPage",
};
</script>

<style scoped>
.plh-page {
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

.plh-image {
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
