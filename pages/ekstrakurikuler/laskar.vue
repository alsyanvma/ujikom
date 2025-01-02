<template>
  <div class="laskar-pusaka-page">
    <div class="container">
      <h1>Ekstrakurikuler Laskar Pusaka</h1>
      <div class="content">
        <!-- Foto -->
        <div class="image-container">
          <img src="~/assets/img/sr.jpg" alt="Laskar Pusaka" class="laskar-pusaka-image" />
        </div>

        <!-- Deskripsi -->
        <div class="description-container">
          <h2>Deskripsi Ekstrakurikuler Laskar Pusaka</h2>
          <p>
            Ekstrakurikuler Laskar Pusaka di SMKN 4 Tasikmalaya adalah wadah bagi siswa yang memiliki minat dalam
            melestarikan budaya dan sejarah Indonesia. Kegiatan ini bertujuan untuk memperkenalkan dan mengajarkan
            nilai-nilai kebangsaan, cinta tanah air.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "LaskarPusakaPage",
};
</script>

<style scoped>
.laskar-pusaka-page {
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

.laskar-pusaka-image {
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
