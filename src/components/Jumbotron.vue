<template>
  <div class="jumbotron jumbotron-fluid">
    <div class="container">
      <h1 class="display-4 text-white">CRX. Accelerating your impact. </h1>
      <p class="lead text-white">
        Apply for community development funding today
      </p>
      <form class="input-group mt-3 email-input" action="https://formspree.io/devjbull@gmail.com"
      method="POST">
        <input type="email" class="form-control" name="email" placeholder="Email Address">
        <div class="input-group-append">
          <button class="btn email-btn" type="submit" >Get Started</button>
        </div>
      </form>
    </div>
  </div>
</template>
<script>
export default {
  name: 'Jumbotron',
};
</script>
<style scoped>
.email-input {
  width: 30%;
}

.email-btn {
  background: #3D68A3;
  color: white;
}

.row {
  margin-left: 0px!important;
  margin-right: 0px!important;
}

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
  background-attachment: fixed;
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

@media (max-width: 991.98px) {
  .email-input {
    width: 45%;
  }
}

@media (max-width: 767px) {
  .email-input {
    width: 60%;
  }
}

@media (max-width: 576px) {
  .email-input {
    width: 70%;
  }
}

@media (max-width: 400px) {
  .email-input {
    width: 100%;
  }
}

</style>

