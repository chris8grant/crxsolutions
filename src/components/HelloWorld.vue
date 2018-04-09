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
      <div class="container-fluid p-5"> 
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
    <div class="container-fluid p-5" id="story">
      <div class="container p-5">
        <h2 class="t">Our Story</h2>
        <p class="pt-4 lead">CRX launched in 2018 to increase access to capital and credit in low and moderate-income communities. Today, we are building world-class technology that connects banks with businesses and non-profit organizations like you! CRX is fundamentally transforming the way impactful businesses and non-profits are financed and building the financial marketplace of the future.
        </p>
      </div>
    </div>
    <div class="container-fluid p-5" id="get-started">
      <div class="p-5">
        <h2 class="t text-white">Get Started</h2>
        <!-- <div class="container" id="get-started-form-container"> -->
          <form class="form-group email-input row justify-content-md-center" action="https://formspree.io/cgranted@stanford.edu"
        method="POST">
            <input type="text" class="form-control mb-3 transparent col-xs-12 col-md-8" name="name" placeholder="Name">       
            <input type="email" class="form-control mb-3 transparent col-xs-12 col-md-8 " name="email" placeholder="Email Address">
            <input type="text" class="form-control mb-3 transparent col-xs-12 col-md-8" name="organization" placeholder="Name of Organization">
            <input type="text" class="form-control mb-3 transparent col-xs-12 col-md-8" name="location" placeholder="City, Zip">
            <input type="number" class="form-control transparent mb-3 col-xs-12 col-md-8" name="funding" @focus="funding = 10000" v-model="funding" placeholder="Funding Amount">
            <input type="submit" class="btn btn-primary col-xs-12 col-md-5" id="get-started-btn" value="Get Started">
          </form>
        <!-- </div> -->
      </div>
    </div>
    <div class="container-fluid p-5" id="team">
      <div class="container p-5">
        <h2 class="t pb-3">Our Team</h2>
        
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
  data() {
    return {
      funding: 'How much funding are you seeking?',
    };
  },
};
</script>

<style scoped>
.transparent {
  background: none;
  border: 1px solid white;
  color: #fff !important;
  height: 45px;
}

.transparent:focus {
  background: none;
}

.transparent::placeholder {
  color: white;
  font-weight: 500;
}

/* #get-started-form-container {
  width: 75%;
} */

#get-started-btn {
  height: 45px;
  background: #3D68A3;
  border: 1px solid #3D68A3;
}
.team-row {
  justify-content: space-around!important;
}
.profile {
  border-radius: 5px;
  border: 1px solid #e3e3e3;
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
    linear-gradient(rgba(0, 0, 0, .3),rgba(0, 0, 0,.75)),
    url(../assets/summer.jpg);
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  margin-bottom: 0px;
  background-attachment: fixed;
}

#get-started {
  display: flex;
  flex-direction: column;
  /* justify-content: center; */
  /* align-content: center; */
  height: 86vh;
  background-image:
    linear-gradient(rgba(0, 0, 0, .7),rgba(0, 0, 0,.7)),
    url(../assets/get-started.jpg);
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
  .p-5 {
    padding: 1rem!important;
  }
  /* #get-started-form-container {
    width: 100%;
  } */
}

</style>
