<template>
  <div class="about">
    <!-- <h1>This is an about page</h1> -->
    <AboutComp />
  </div>
</template>

<script>
import AboutComp from '../components/AboutComp.vue';
  export default {
    components : {
      AboutComp
    }
  }
</script>

<style scoped>

.about{
    overflow: hidden;
   /* padding: 10px; */
    min-height: 100vh;
    /* padding: 70px; */
}

</style>