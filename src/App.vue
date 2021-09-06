<template>
  <div class="top">
    <Navbar />
    <div class="logo col-lg-6 offset-lg-3 col-md-8 offset-md-2 col-sm-8 offset-sm-2 col-10">
      <img alt="Vue logo" src="./assets/nile-logo.png" class="img-fluid">
    </div>
    <Main class="text-center" msg="Online Business Exhibition, All At Your Fingertips"/>
  </div>
</template>

<script>
import Main from './components/Main.vue'
import Navbar from './components/Navbar.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Main
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center;
  color: #2c3e50;
  margin-top: 60px; */
}

.top {
  background: url('assets/top-bg1.png');
  background-size:cover;
  background-position: center;
  aspect-ratio: 32/9;
}

.logo {
  margin:0 auto;
}
</style>
