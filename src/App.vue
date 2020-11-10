<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <p>Here a couple icons:</p>
    <vue-remixicon name="bank" type="line" />
    <vue-remixicon name="building" type="fill" />
    <p>Above, a couple icons.</p>
  </div>
</template>

<script>
import vueRemixicon from "@katalonne/vue-remixicon";

export default {
  name: "App",
  components: {
    vueRemixicon,
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
