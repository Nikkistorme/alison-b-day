<template>
  <div id="app">
    <!-- melody -> chelsea -> caitlin -> other -> letter -->
    <div class="column">
      <img alt="Alison is the best" src="./assets/melody1.jpg">
      <img alt="Alison is the best" src="./assets/letter1.png">
      <img alt="Alison is the best" src="./assets/other2.jpg">
      <img alt="Alison is the best" src="./assets/caitlin3.jpg">
      <img alt="Alison is the best" src="./assets/chelsea4.jpg">
      <img alt="Alison is the best" src="./assets/melody5.jpg">
      <img alt="Alison is the best" src="./assets/letter5.jpg">
    </div>
    <div class="column">
      <img alt="Alison is the best" src="./assets/chelsea1.jpg">
      <img alt="Alison is the best" src="./assets/melody2.jpg">
      <img alt="Alison is the best" src="./assets/letter2.jpg">
      <img alt="Alison is the best" src="./assets/other3.jpg">
      <img alt="Alison is the best" src="./assets/caitlin4.jpg">
      <img alt="Alison is the best" src="./assets/chelsea5.jpg">
      <img alt="Alison is the best" src="./assets/melody6.jpg">
    </div>
    <div class="column">
      <img alt="Alison is the best" src="./assets/caitlin1.jpg">
      <img alt="Alison is the best" src="./assets/chelsea2.jpg">
      <img alt="Alison is the best" src="./assets/melody3.jpg">
      <img alt="Alison is the best" src="./assets/letter3.png">
      <img alt="Alison is the best" src="./assets/other4.jpg">
      <img alt="Alison is the best" src="./assets/caitlin5.jpg">
      <img alt="Alison is the best" src="./assets/chelsea6.jpg">
    </div>
    <div class="column">
      <img alt="Alison is the best" src="./assets/other1.jpg">
      <img alt="Alison is the best" src="./assets/caitlin2.jpg">
      <img alt="Alison is the best" src="./assets/chelsea3.jpg">
      <img alt="Alison is the best" src="./assets/melody4.jpg">
      <img alt="Alison is the best" src="./assets/letter4.jpg">
      <img alt="Alison is the best" src="./assets/other5.jpg">
      <img alt="Alison is the best" src="./assets/caitlin6.png">
    </div>
  </div>
</template>

<script>

export default {
  name: 'App',
}
</script>

<style>
* {
  box-sizing: border-box;
}
html {
  background-color: black;
}
body {
  margin: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  display: flex;
  flex-wrap: wrap;
  background-color: black;
}
.column {
  flex: 1;
  max-width: 25%;
  min-width: 250px;
  height: min-content;
}
img {
  max-width: 100%;
  display: block;
  width: auto;
  height: auto;
}
</style>
