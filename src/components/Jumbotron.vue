<template>
  <div class="jumbotron jumbotron-fluid">
    <div class="container">
      <h1 class="display-4 text-white">CRX Solutions</h1>
      <p class="lead text-white">
        This is a modified jumbotron that occupies the entire horizontal space of its parent.
      </p>
      <button class="btn contact-btn btn-outline-light text-uppercase btn-lg">Contact Us</button>
    </div>
  </div>
</template>
<script>
export default {
  name: 'Jumbotron',
};
</script>
<style scoped>
.jumbotron {
  display: flex;
  align-content: center;
  height: 80vh;
  background-image:
    linear-gradient(rgba(0, 0, 0, 0),rgba(0, 0, 0,.55)),
    url(../assets/adventure.jpg);
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  margin-bottom: 0px;
}

.container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  /* height: 100%; */
}

.contact-btn {
  border-radius: 1px;
  font-size: 14px;
  padding: 11px 26px;
}
</style>

