<template>
  <!-- Navbar -->
  <Navbar />
  <!-- End of Navbar -->

  <!-- Explore -->
  <Explore />
  <!-- End of Explore -->

  <!-- Release -->
  <Release />
  <!-- End of Release -->

  <router-view />
</template>

<script>
import Navbar from "@/components/Navbar.vue";
import Explore from "@/components/Explore.vue";
import Release from "@/components/Release.vue";

export default {
  name: "App",
  components: {
    Navbar, Explore,
    Release
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');

* {
  margin: 0px;
  padding: 0px;
}

body {
  scroll-behavior: smooth;
}

body::-webkit-scrollbar {
  width: 15px;
}

body::-webkit-scrollbar-track {
  background: #374151;
}

body::-webkit-scrollbar-thumb {
  background-color: #262629;
  /* color of the scroll thumb */
  border-radius: 20px;
  /* roundness of the scroll thumb */
  border: 3px solid #192026;
  /* creates padding around scroll thumb */
}

#app {
  font-family: 'Poppins', sans-serif;
  background: #192026;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
