<template>
  <div id="app">
    <img src="./assets/logo.png">
    <div>
      <p>
        If iView is successfully added to this project, you'll see an
        <!-- <code v-text="'<Button>'"></code> -->
        below
      </p>
      <router-link to="/Home">home </router-link>

        <router-link to="/About"> about</router-link>

        <router-view></router-view>
    </div>
  </div>
</template>

<script>
// import HelloWorld from '@/components/HelloWorld.vue'
// import Home from '@/views/Home.vue'
// import About from '@/views/About.vue'

export default {
  name: 'app',
  components: {
    // HelloWorld
    // Home,
    // About
  }
}
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
