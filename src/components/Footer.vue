<template>
  <footer class="pt-5 pb-5">
    <h3 class="text-white display-3">CRX</h3>
    <p class="text-white mb-0">680 Serra Street, C146</p>
    <p class="text-white">Stanford, CA 94305</p>
    <div class="row text-white text-center"> <p>&copy; Copyright {{ year }}</p> <a class="text-white ml-3" href="mailto:youraddr@domain.tld">cgranted@stanford.edu</a> </div>
  </footer>
</template>
<script>
export default {
  name: 'Footer',
  data() {
    return {
      year: '',
    };
  },
  created() {
    this.year = new Date().getFullYear();
  },
};
</script>
<style scoped>
.row {
  justify-content: center;
  margin-left: 0px!important;
  margin-right: 0px!important;
}
footer {
  background: #3D68A3;
}
</style>

