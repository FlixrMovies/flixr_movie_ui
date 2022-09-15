<template>
  <router-view />
</template>

<script>
import HomeView from "@/views/HomeView.vue";

export default {
  name: "App",
  components: {
    HomeView
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
  height: max-content;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

@media screen and (max-width: 890px) {
  #app {
    height: auto;
  }
}
</style>
