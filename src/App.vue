<template>
  <div id="app">
    <h1>Calculator Vue</h1>
    <CalculatorVue/>
  </div>
</template>

<script>
import CalculatorVue from './main/CalculatorVue.vue'
export default {
  components: { CalculatorVue }
}
</script>

<style scoped>
@font-face {
  font-family: "RobotoMono";
  src: url('./fonts/RobotoMono-Thin.ttf');
}

* {
  font-family: 'RobotoMono', monospace;
}

body {
  margin: 0;
}

#app {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
  text-align: center;
  color: white;
  background: linear-gradient(to right, rgb(83, 105, 118), rgb(41, 46, 73));
}
</style>