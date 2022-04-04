
<template>
  <h1>App Base</h1>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/Login">Login</router-link> |
    <router-link to="/Register">Register</router-link> |
    <button>Logout</button>
  </nav>
  <router-view/>
</template>
<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
