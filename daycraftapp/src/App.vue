<template>
  <navbar />
  <bodytext />
  <advicedisplay />
  <footerc />
  <days />
  <habits />
</template>

<script>
import navbar from "./components/navbar";
import bodytext from "./components/bodytext";
import advicedisplay from "./components/advicedisplay";
import habits from "./components/habits";
import days from "./components/days";
import footerc from "./components/footerc";
export default {
  name: "App",
  components: { navbar, bodytext, advicedisplay, habits, days, footerc },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 2vh;
  border: 3px solid red;
}
</style>
