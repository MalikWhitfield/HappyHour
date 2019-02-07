<template>
  <div class="container-fluid">
    <nav class="navbar navbar-light bg-light justify-content-between" style="width: 100vw">
      <i class="fas fa-cocktail"></i>
      <a class="navbar-brand">My List</a>
      <form class="form-inline">
        <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
      </form>
      <div class="collapse navbar-collapse" id="navbarSupportedContent1">
        <!-- Links -->
        <ul class="navbar-nav mr-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#">Home
              <span class="sr-only">(current)</span>
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Features</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Pricing</a>
          </li>
        </ul>
        <!-- Links -->
      </div>
    </nav>
    <!-- Collapsible content -->
  </div>
</template>

<script>
export default {
  name: "Navbar",
  data() {
    return {};
  },
  computed: {},
  methods: {}
};
</script>

<style>
.logo-size {
  width: 250px;
  height: 250px;
}
</style>