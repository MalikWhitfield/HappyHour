<template>
  <div class="home container-fluid">
    <navbar></navbar>
    <!-- GET RID OF THE GUTTER ON THE LEFT -->
    <h1>Happy Hour!</h1>
    <i class="fas fa-cocktail fa-4x"></i>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue"; //Figure out how to make this work without Helloworld
import Navbar from "@/components/Navbar.vue";
export default {
  name: "home",
  components: {
    HelloWorld,
    Navbar
  }
};
</script>
