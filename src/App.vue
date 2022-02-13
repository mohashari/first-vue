<template>
  <h2>Hello {{ name }}</h2>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      name: "Muklis",
    };
  },
};
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
