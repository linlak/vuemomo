<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <MomoQrPayment externalId="201-2445-123" amount="10"></MomoQrPayment>
  </div>
</template>

<script>
import MomoQrPayment from './components/MomoQrPayment.vue'

export default {
  name: 'App',
  components: {
    MomoQrPayment
  }
}
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
