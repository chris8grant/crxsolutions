<template>
<nav class="navbar  fixed-top navbar-expand-lg navbar-light bg-light" id="navbar">
  <a class="navbar-brand" href="#">CRX</a>
  <button
    class="navbar-toggler"
    type="button"
    data-toggle="collapse"
    data-target="#navbarNavDropdown"
    aria-controls="navbarNavDropdown"
    aria-expanded="false"
    aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse justify-content-end" id="navbarNavDropdown">
    <ul class="navbar-nav">
      <li class="nav-item active">
        <a class="nav-link" href="#"> <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#solution">Solutions</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#story">Our Story</a>
      </li>
      <li class="nav-item dropdown">
        <a class="nav-link" href="#team">
          Team
        </a>
      </li>
    </ul>
  </div>
</nav>
</template>

<script>
export default {
  name: 'Navbar',
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
