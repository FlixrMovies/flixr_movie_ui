<template>
  <div class="home">
    <!-- Navbar -->
    <Navbar />
    <!-- End of Navbar -->

    <!-- Explore -->
    <Explore />
    <!-- End of Explore -->

    <!-- Release -->
    <Release />
    <!-- End of Release -->
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";
import Explore from "@/components/Explore.vue";
import Release from "@/components/Release.vue";

export default {
  name: 'HomeView',
  components: {
    Navbar, Explore,
    Release
  }
}
</script>
