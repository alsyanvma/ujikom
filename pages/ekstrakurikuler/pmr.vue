<template>
  <div class="pmr-page">
    <div class="container">
      <h1>Ekstrakurikuler Palang Merah Remaja</h1>
      <div class="content">
        <!-- Foto -->
        <div class="image-container">
          <img src="~/assets/img/pmr.jpg" alt="Palang Merah Remaja" class="pmr-image" />
        </div>

        <!-- Deskripsi -->
        <div class="description-container">
          <h2>Deskripsi Ekstrakurikuler Palang Merah Remaja</h2>
          <p>
            Ekstrakurikuler Palang Merah Remaja (PMR) di SMKN 4 Tasikmalaya adalah wadah bagi siswa untuk mengembangkan
            kemampuan di bidang sosial, kemanusiaan, dan kesehatan. Kegiatan ini bertujuan untuk menumbuhkan rasa empati
            dan kepedulian terhadap sesama, serta memberikan pengetahuan dan keterampilan dalam memberikan pertolongan
            pertama, penyuluhan kesehatan, serta aksi sosial di masyarakat.
          </p>
          <p>
            Setiap tahunnya, ekstrakurikuler ini mengadakan berbagai kegiatan, seperti pelatihan pertolongan pertama,
            kampanye kesehatan, bakti sosial, serta membantu dalam kegiatan sosial lainnya. Para anggota PMR juga aktif
            berpartisipasi dalam kegiatan kemanusiaan dan menjadi relawan di berbagai acara.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "PMRPage",
};
</script>

<style scoped>
.pmr-page {
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

.pmr-image {
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
