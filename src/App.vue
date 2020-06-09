<template>
  <div id="app">
    <HomePage/>
  </div>
</template>

<script>
import HomePage from "./modules/HomePage.vue";

export default {
  name: "App",
  components: {
    HomePage
  }
};
</script>

<style>
@font-face {
  font-family: "Source Sans Pro";
  src: url("assets/fonts/Source_Sans_Pro/SourceSansPro-Black.ttf") format("truetype");
  font-weight: 900;
}
@font-face {
  font-family: "Source Sans Pro";
  src: url("assets/fonts/Source_Sans_Pro/SourceSansPro-Bold.ttf") format("truetype");
  font-weight: bold;
}
@font-face {
  font-family: "Source Sans Pro";
  src: url("assets/fonts/Source_Sans_Pro/SourceSansPro-Italic.ttf") format("truetype");
  font-style: italic;
}
@font-face {
  font-family: "Source Sans Pro";
  src: url("assets/fonts/Source_Sans_Pro/SourceSansPro-Regular.ttf") format("truetype");
  font-weight: 500;
}
@font-face {
  font-family: "Mandatory Plaything";
  src: url("assets/fonts/Mandatory_Plaything/Mandatory_Plaything.otf") format("opentype");
  font-weight: 500;
}

body {
  margin: 0;
  background: url("assets/img/bg-homepage.png") center no-repeat;
  background-size: cover;
}
#app {
  font-family: "Source Sans Pro";
  text-align: center;
  color: #2c3e50;
  display: block;
  width: 100vw;
  min-height: 100vh;
  padding: 0 50px;
}
</style>
