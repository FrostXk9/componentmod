<template>

  <div class="position-relative overflow-hidden p-3 p-md-5 m-md-3 text-center" id="landingPage">
    
    <div class="col-md-6 p-lg-5 mx-auto my-5">

      <h1 class="display-3 fw-bold">Designed for engineers</h1>

      <h3 class="fw-normal text-black mb-3">Build anything you want with Aperture</h3>

      <div class="d-flex gap-3 justify-content-center lead fw-normal">

        <ButtonComp />

      </div>

    </div>
    
  </div>

</template>

<script>
import ButtonComp from './ButtonComp.vue';
export default {
  components : {
    ButtonComp
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
#landingPage{
  background-color: rgba(0, 0, 0, 0);
}
a {
  color: #42b983;
}

</style>
