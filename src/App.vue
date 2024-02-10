<template>

  <!-- <LoaderCompVue /> -->

  <NavbarComp />

  <router-view/>

  <FooterComp />
</template>

<script>
import NavbarComp from './components/NavigationBar.vue';
import LoaderCompVue from './components/LoaderComp.vue';
import FooterComp from './components/FooterComp.vue';

export default {

  components : {
    NavbarComp,
    LoaderCompVue,
    FooterComp
  }

}
</script>

<style>

::-webkit-scrollbar{
  display: none;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}

</style>
