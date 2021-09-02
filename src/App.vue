<template>
  <div id="app">
    <!-- melody -> chelsea -> caitlin -> other -> letter -->
    <div class="column">
      <img alt="Alison is the best" src="./assets/melody1.jpg">
      <img alt="Alison is the best" src="./assets/letter1.png">
      <img alt="Alison is the best" src="./assets/other2.jpg">
      <img alt="Alison is the best" src="./assets/caitlin3.jpg">
      <img alt="Alison is the best" src="./assets/letter9.jpg">
      <img alt="Alison is the best" src="./assets/chelsea2.jpg">
      <img alt="Alison is the best" src="./assets/letter13.jpg">
      <img alt="Alison is the best" src="./assets/chelsea4.jpg">
      <img alt="Alison is the best" src="./assets/melody5.jpg">
      <img alt="Alison is the best" src="./assets/letter5.jpg">
      <img alt="Alison is the best" src="./assets/other6.jpg">
      <img alt="Alison is the best" src="./assets/caitlin7.jpg">
      <img alt="Alison is the best" src="./assets/letter14.jpg">
      <img alt="Alison is the best" src="./assets/chelsea8.jpg">
      <img alt="Alison is the best" src="./assets/letter11.jpg">
      <img alt="Alison is the best" src="./assets/melody9.jpg">
      <img alt="Alison is the best" src="./assets/letter21.jpg">
      <img alt="Alison is the best" src="./assets/other10.jpg">
      <img alt="Alison is the best" src="./assets/chelsea13.jpg">
    </div>
    <div class="column">
      <img alt="Alison is the best" src="./assets/letter24.jpg">
      <img alt="Alison is the best" src="./assets/chelsea1.jpg">
      <img alt="Alison is the best" src="./assets/melody2.jpg">
      <img alt="Alison is the best" src="./assets/letter2.jpg">
      <img alt="Alison is the best" src="./assets/other3.jpg">
      <img alt="Alison is the best" src="./assets/caitlin4.jpg">
      <img alt="Alison is the best" src="./assets/chelsea5.jpg">
      <img alt="Alison is the best" src="./assets/melody6.jpg">
      <img alt="Alison is the best" src="./assets/letter6.png">
      <img alt="Alison is the best" src="./assets/chelsea15.jpg">
      <img alt="Alison is the best" src="./assets/chelsea16.jpg">
      <img alt="Alison is the best" src="./assets/caitlin8.jpg">
      <img alt="Alison is the best" src="./assets/letter20.jpg">
      <img alt="Alison is the best" src="./assets/chelsea9.jpg">
      <img alt="Alison is the best" src="./assets/other13.jpg">
      <img alt="Alison is the best" src="./assets/letter10.jpg">
      <img alt="Alison is the best" src="./assets/other14.jpg">
      <img alt="Alison is the best" src="./assets/chelsea11.jpg">
      <img alt="Alison is the best" src="./assets/chelsea14.jpg">
    </div>
    <div class="column">
      <img alt="Alison is the best" src="./assets/other17.jpeg">
      <img alt="Alison is the best" src="./assets/letter23.png">
      <img alt="Alison is the best" src="./assets/caitlin1.jpg">
      <img alt="Alison is the best" src="./assets/melody3.jpg">
      <img alt="Alison is the best" src="./assets/letter3.png">
      <img alt="Alison is the best" src="./assets/letter16.jpg">
      <img alt="Alison is the best" src="./assets/caitlin5.jpg">
      <img alt="Alison is the best" src="./assets/chelsea6.jpg">
      <img alt="Alison is the best" src="./assets/letter17.jpg">
      <img alt="Alison is the best" src="./assets/other12.jpg">
      <img alt="Alison is the best" src="./assets/letter24.png">
      <img alt="Alison is the best" src="./assets/letter7-2.jpg">
      <img alt="Alison is the best" src="./assets/other8.jpg">
      <img alt="Alison is the best" src="./assets/other15.jpg">
      <img alt="Alison is the best" src="./assets/caitlin9.jpg">
      <img alt="Alison is the best" src="./assets/chelsea10.jpg">
      <img alt="Alison is the best" src="./assets/letter22.jpg">
      <img alt="Alison is the best" src="./assets/chelsea12.jpg">
    </div>
    <div class="column">
      <img alt="Alison is the best" src="./assets/other1.jpg">
      <img alt="Alison is the best" src="./assets/letter12.jpg">
      <img alt="Alison is the best" src="./assets/caitlin2.jpg">
      <img alt="Alison is the best" src="./assets/chelsea3.jpg">
      <img alt="Alison is the best" src="./assets/letter19.jpg">
      <img alt="Alison is the best" src="./assets/melody4.jpg">
      <img alt="Alison is the best" src="./assets/letter4.jpg">
      <img alt="Alison is the best" src="./assets/other5.jpg">
      <img alt="Alison is the best" src="./assets/caitlin6.png">
      <img alt="Alison is the best" src="./assets/letter15.jpg">
      <img alt="Alison is the best" src="./assets/chelsea7.jpg">
      <img alt="Alison is the best" src="./assets/melody8.jpg">
      <img alt="Alison is the best" src="./assets/letter18.jpg">
      <img alt="Alison is the best" src="./assets/letter8-2.jpg">
      <img alt="Alison is the best" src="./assets/other9.jpg">
      <img alt="Alison is the best" src="./assets/other11.jpg">
      <img alt="Alison is the best" src="./assets/other18.jpeg">
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
  flex: 25%;
  max-width: 25%;
  min-width: 250px;
  height: min-content;
}
img {
  display: block;
  width: 100%;
}
  @media (max-width: 1000px) {
    .column {
      flex: calc(100% / 3);
      max-width: calc(100% / 3);
    }
  }
  @media (max-width: 750px) {
    .column {
      flex: 50%;
      max-width: 50%;
    }
  }
  @media (max-width: 500px) {
    .column {
      flex: 100%;
      max-width: 100%;
    }
  }
</style>>

