<template>
  <h1>Vue Calculator</h1>
  <CalculatorVue />
</template>

<script>
import CalculatorVue from './components/main/CalculatorVue.vue';
export default {
  name: "App",
  components: { CalculatorVue }
}
</script>

<style>
body {
  background: linear-gradient(#010101, #9198e5);
}

#app {
  display: flex;
  flex-direction: column;
  height: 100vh;
  justify-content: center;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #fff;
  margin-top: 60px;
  align-items: center;

}
</style>
