<template>
  <img
    alt="Flow logo"
    width="200"
    src="https://cryptologos.cc/logos/flow-flow-logo.png?v=010"
  />
  <HelloFlow msg="Hello Flow" />
</template>

<script>
import HelloFlowVue from "./components/HelloFlow.vue";
export default {
  name: "App",
  components: {
    HelloFlow: HelloFlowVue,
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
