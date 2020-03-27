<template>
  <div id="app">
    <MainPage />
  </div>
</template>

<script>
import MainPage from "./components/MainPage.vue";

export default {
  name: "App",
  components: {
    MainPage
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
  margin-top: 60px;
}

body {
  margin: 0 auto;
  max-width: 40rem;
  width: 100%;
  padding: var(--rhythm);
}
</style>
