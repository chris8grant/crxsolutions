<template>
  <main>
    <div class="container p-5" id="about">
      <!-- <h2>About</h2> -->
      <div class="container">
        <p class="lead">
          CRX is designed to connect your funding needs with banks that are genuinely interested in supporting you.
        </p>
      </div>
    </div>
    <div class="jumbotron jumbotron-fluid overflow-scroll" id="solution">
      <div class="container-fluid"> 
        <h2 class="text-white pb-3">How it Works</h2>
        <!-- <p class="text-white mb-5 lead">Our product is designed to connect your funding needs with banks that are genuinely interested in supporting you. </p> -->
        <div class="row">
          <div class="col mb-3">
            <div class="tint p-3">
              <img src="../assets/create-profile.svg" height="125" width="75" class="pt-3"/>
              <p class="text-white pt-3">Create a profile for your business or non-profit. </p>
            </div>
          </div>
          <div class="col mb-3 hide-overflow">
            <div class="tint p-3">
              <img src="../assets/analyze.svg" height="125" width="75" class="pt-3"/>
              <p class="text-white pt-3">We analyze and share your profile with banks seeking quality investment opportunities. </p>
            </div>
          </div>
          <div class="col mb-3">
            <div class="tint p-3">
              <img src="../assets/verified.svg" height="125" width="75" class="pt-3"/>
              <p class="text-white pt-3">We notify you when CRX finds a funding match.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container-fluid p-2" id="story">
      <div class="container p-5">
        <h2 class="t">Our Story</h2>
        <p class="pt-4 lead">CRX launched in 2018 to increase access to capital and credit in low and moderate-income communities. Today, we've built world-class technology that connects banks with impactful community development projects that meet their Community Reinvestment Act compliance obligations. CRX is fundamentally transforming the way community development projects are financed and building the financial marketplace of the future. 
        </p>
      </div>
    </div>
    <div class="container-fluid p-2 pt-5" id="team">
      <h2 class="t pb-3">Our Team</h2>
      <div class="container">
        <div class="row team-row">
          <div class="col-xs-3">
            <img src="../assets/chris-profile.jpeg" width="200" height="200" class="profile"/>
            <h5 class="pt-3">Chris</h5>
            <p>CEO</p>
          </div>
          <div class="col-xs-3">
            <img src="../assets/devon-profile.jpeg" width="200" height="200" class="profile"/>
            <h5 class="pt-3">Devon</h5>
            <p>Engineering</p>
          </div>
          <div class="col-xs-3">
            <img src="../assets/sara-profile.jpeg" width="200" height="200" class="profile"/>
            <h5 class="pt-3">Sara</h5>
            <p>Business Development</p>
          </div>
          <div class="col-xs-3">
            <img src="../assets/kate-profile.png" width="200" height="200" class="profile"/>
            <h5 class="pt-3">Kate</h5>
            <p>Operations</p>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>

<script>

export default {
  name: 'HelloWorld',
};
</script>

<style scoped>
.team-row {
  justify-content: space-around!important;
}
.profile {
  border-radius: 5px;
  /* filter: grayscale(100%); */
}

.overflow-scroll {
  overflow: auto;
}

.hide-overflow {
  overflow: hidden;
}

.col-sm-4 {
  max-width: 24%;
}
.tint {
  height: 260px;
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

#team {
  background: #ece8e8;
}

@media (max-width: 575.98px) {
  .jumbotron {
    height: 170vh;
  }
  .col {
    min-width: 51%;
  }
  .p-5 {
    padding: 1rem!important;
  }
}

</style>
