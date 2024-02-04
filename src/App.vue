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
// import AOS from 'aos'

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
  /* color: #2c3e50; */
  /* https://cdn-images.imagevenue.com/b5/23/64/ME17J4GH_o.png */
  /* background-image: url("https://cdn-images.imagevenue.com/8d/4d/d7/ME17JAM6_o.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  min-height: 100vh;
  min-width: 100%; */
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}

</style>
