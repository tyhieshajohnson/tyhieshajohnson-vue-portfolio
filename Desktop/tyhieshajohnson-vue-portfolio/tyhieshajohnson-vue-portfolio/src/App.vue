<template>
  <!-- <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav> -->
  <nav class="navbar bg-dark border-bottom border-body" data-bs-theme="dark">
  <div class="container">
    <a class="navbar-brand" href="#">
      <img src="/docs/5.3/assets/brand/bootstrap-logo.svg" alt="Bootstrap" width="30" height="24">
    </a>
    <router-link to="/">Home</router-link> 
    <router-link to="/about">About</router-link> 
    <router-link to="/about">About</router-link> 
    <router-link to="/about">About</router-link>
    <router-link to="/about">About</router-link> 
    <router-link to="/about">About</router-link> 
  </div>
  </nav>
  <router-view/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import Main from './components/Main.vue';

export default {
  // name: App,
  // components: [
  //   HelloWorld,
  //   Main
  // ]
}
</script>

<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 5px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
