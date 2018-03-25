<template>
  <main data-spy="scroll" data-target="#navbar" data-offset="0">
    <div class="container" id="borrowers">
      <h2 class="pt-5">Opportunity</h2>
    </div>
    <div class="container-fluid" id="about">
      <div class="container pb-5 pt-5">
        <h2 class="t">Our Story</h2>
        <p class="pt-4">Lorem Ipsum is simply dummy text of the printing and typesetting industry.
          Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,
          when an unknown printer took a galley of type and scrambled it to make a type specimen book.
          It has survived not only five centuries, but also the leap into electronic typesetting,
        </p>
        <p class=" pt-3">Lorem Ipsum is simply dummy text of the printing and typesetting industry.
          Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,
          when an unknown printer took a galley of type and scrambled it to make a type specimen book.
          It has survived not only five centuries, but also the leap into electronic typesetting,
        </p>
      </div>
    </div>
    <div class="jumbotron jumbotron-fluid">
    </div>
  </main>
</template>

<script>

export default {
  name: 'HelloWorld',
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.jumbotron {
  display: flex;
  /* align-content: center; */
  height: 100vh;
  background-image:
    linear-gradient(rgba(0, 0, 0, 0),rgba(0, 0, 0,.55)),
    url(../assets/summer.jpg);
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  margin-bottom: 0px;
  background-attachment: fixed;
}
/* #about {
  background: #3D68A3;
} */

</style>
