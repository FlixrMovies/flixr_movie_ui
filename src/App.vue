<template>
  <!-- Navbar -->
  <Navbar />
  <!-- End of Navbar -->

  <router-view />
</template>

<script>
import Navbar from "@/components/Navbar.vue";

export default {
  name: "App",
  components: {
    Navbar,
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');

* {
  margin: 0px;
  padding: 0px;
}

#app {
  font-family: 'Poppins', sans-serif;
  background: #192026;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
