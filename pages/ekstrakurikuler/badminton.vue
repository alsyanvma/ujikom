<template>
  <div class="basketball-page">
    <div class="container">
      <h1>Ekstrakurikuler Volly</h1>
      <div class="content">
        <!-- Foto -->
        <div class="image-container">
          <img src="~/assets/img/bad.jpg" alt="Basketball" class="basketball-image" />
        </div>

        <!-- Deskripsi -->
        <div class="description-container">
          <h2>Deskripsi Ekstrakurikuler Badminton</h2>
          <p>
            Ekstrakulikuler badminton adalah salah satu ekskul yang dibina dan di kembangkan di SMKN 4 Tasikmalaya,
            badminton/bulu tangkis merupakan salah satu cabang olah raga yang paling banyak digemari oleh siswa siswi
            di SMKN 4Tasikmalaya serta lingkungan masyarakat sekitar pada umum nya. SMKN 4 Tasikmalaya mencoba
            mengembangkan ekstrakurikuler Bulutangkis sebagai cabang olah raga unggulan untuk mewadahi siswa siswi
            nya yang memiliki hobi dan bakat di olah raga tersebut.
          </p>
          <p>
            Serta mempersiapkan siswa siswi anggota ekstrakuler bulutangkis untuk tidak hanya menguasai permainan
            bulutangkis,
            namun juga siap fisik dan mental anak-anak dalam menghapi event event olah raga antar siswa SMK sebagai
            contoh
            adalah O2SN tingkat kabupaten yang selalu diselengarakan oleh pemerintah setiap tahunya dan selalau diikuti
            oleh siswa siswi, serta event – event olah raga lain.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "BasketballPage",
};
</script>

<style scoped>
.basketball-page {
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

.basketball-image {
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