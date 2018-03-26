<template>
  <main data-spy="scroll" data-target="#navbar" data-offset="0">
    <div class="container p-5">
      <h2>Test</h2>
      <p>
        Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,
        when an unknown printer took a galley of type and scrambled it to make a type specimen book.
        It has survived not only five centuries, but also the leap into electronic typesetting,
      </p>
    </div>
    <div class="jumbotron jumbotron-fluid">
      <div class="container"> 
        <h2 class="text-white">Make Data Driven Decisions</h2>
        <p class="text-white mb-5">Be confident in your investments.</p>
        <div class="row">
          <div class="col mb-3">
            <div class="tint p-3">
              <h5 class="text-uppercase text-white pt-3">Test</h5>
              <p class="text-white">There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable.</p>
            </div>
          </div>
          <div class="col mb-3">
            <div class="tint p-3">
              <h5 class="text-uppercase text-white pt-3">Test</h5>
              <p class="text-white">There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable.</p>
            </div>
          </div>
          <div class="col mb-3">
            <div class="tint p-3">
              <h5 class="text-uppercase text-white pt-3">Test</h5>
              <p class="text-white">There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container-fluid" id="about">
      <div class="container p-5">
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
    <div class="p-5">
      

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

.col-sm-4 {
  max-width: 24%;
}
.tint {
  background: rgba(34, 34, 34, 0.4);
}
.row {
  justify-content: center;
  padding: 15px;
  margin-left: 0px!important;
  margin-right: 0px!important;
}
.jumbotron {
  display: flex;
  flex-direction: column;
  /* justify-content: center; */
  /* align-content: center; */
  height: 86vh;
  background-image:
    linear-gradient(rgba(0, 0, 0, 0),rgba(0, 0, 0,.75)),
    url(../assets/summer.jpg);
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  margin-bottom: 0px;
  background-attachment: fixed;
}
@media (max-width: 575.98px) {
  .jumbotron {
    height: 170vh;
  }
  .col {
    min-width: 51%;
  }
}

</style>
