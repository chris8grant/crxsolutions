<template>
  <footer class="pt-5 pb-5">
    <h3 class="text-white">CRX</h3>
    <div class="row">
      <div class="col text-white"> &copy; Copywrite {{ year }} </div>
    </div>
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
  margin-left: 0px!important;
  margin-right: 0px!important;
}
footer {
  background: #3D68A3;
}
</style>

