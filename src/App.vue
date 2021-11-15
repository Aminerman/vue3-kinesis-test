<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
  <kinesis-container class="container">
    <kinesis-element :strength="10" type="depth">
      <img alt="Vue logo" src="./assets/logo.png" />
    </kinesis-element>
    <kinesis-element class="title" type="depth" :strength="20" tag="h1">
      vue3-kinesis
    </kinesis-element>
  </kinesis-container>
  <HelloWorld msg="Hello Vue 3 + Vite" />
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

.container {
  background-color: aliceblue;
  position: relative;
}

.title {
  position: absolute;
  margin: auto;
  left: 0;
  right: 0;
  bottom: 0;
}
</style>
