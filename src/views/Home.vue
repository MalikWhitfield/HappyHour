<template>
  <div class="home container-fluid">
    <navbar></navbar>
    <h1>Happy Hour!</h1>
    <i class="fas fa-cocktail fa-4x"></i>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import Navbar from "@/components/Navbar.vue";
export default {
  name: "home",
  components: {
    HelloWorld,
    Navbar
  }
};
</script>
