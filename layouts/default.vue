<template>
    <div>
      <navbar />
      <slot />
      <Footer />
    </div>
  </template>
  
  
  <script>
  import Footer from '~/components/footer.vue';
  
  export default {
    components: {
      Footer,
    },
  };
  </script>