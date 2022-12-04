<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header.vue'
import Add from './components/Add.vue'
</script>

<template>
<div class="container mx-auto">
<Header/>
  <Add hidden />
  <img id="logo" class="m-auto" alt="" src="https://www.kindpng.com/picc/m/586-5866074_walmart-logo-white-png-walmart-logo-black-and.png" />
  <HelloWorld msg="Hello Vue 3 + Vite" />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
#logo {
  width:75%;
  height:50px;
}
</style>
