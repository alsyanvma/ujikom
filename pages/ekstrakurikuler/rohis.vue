<template>
  <div class="rohis-page">
    <div class="container">
      <h1>Ekstrakurikuler Rohis</h1>
      <div class="content">
        <!-- Foto -->
        <div class="image-container">
          <img src="~/assets/img/rohis.png" alt="Rohis" class="rohis-image" />
        </div>

        <!-- Deskripsi -->
        <div class="description-container">
          <h2>Deskripsi Ekstrakurikuler Rohis</h2>
          <p>
            Ekstrakurikuler Rohis (Rohani Islam) di SMKN 4 Tasikmalaya merupakan sarana bagi siswa untuk meningkatkan
            pemahaman dan pengamalan ajaran agama Islam. Kegiatan ini bertujuan untuk membentuk karakter siswa yang
            berakhlak mulia, memperdalam ilmu agama, serta memperkuat ukhuwah Islamiyah di kalangan sesama siswa.
          </p>
          <p>
            Setiap tahunnya, ekstrakurikuler Rohis mengadakan berbagai kegiatan seperti pengajian rutin, kajian ilmu
            agama, dan berbagai kegiatan sosial untuk membantu sesama, baik dalam lingkungan sekolah maupun masyarakat.
            Kami juga aktif mengadakan kegiatan perayaan hari besar Islam serta berbagai lomba yang mendukung
            pengembangan diri di bidang agama.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "RohisPage",
};
</script>

<style scoped>
.rohis-page {
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

.rohis-image {
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
