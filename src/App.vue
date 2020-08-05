<template>
  <div id="app">
    <VueWeather />
  </div>
</template>

<script>
import VueWeather from "./components/VueWeather.vue";

export default {
  components: {
    VueWeather,
  },
};
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css?family=Anton");
@import url("https://use.fontawesome.com/releases/v5.8.2/css/all.css");

body {
  margin: 0;
  padding: 0;
}

#app {
  font-family: "Anton", Arial, Helvetica, sans-serif;
  font-size: 1rem;
  letter-spacing: 1px;
  color: #322f42;
  width: 100%;
  min-height: 100vh;
  background-size: cover;
  overflow: hidden;
}
</style>
