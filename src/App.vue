<template>
  <div id="app">
    <img id="logo" src="./assets/logo.png">
    <router-view/>


  <div class="footer">© Ever404 2019 &nbsp;&nbsp; By sengle &nbsp;&nbsp; All Rights Reserved</div>
  </div>
</template>

<script>
import blog from "./components/Blog.vue";
export default {
  name: "App",
  components: {
    blog
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 40px;
}

#logo {
  width: 50%;
  height: 50%;
}
</style>
