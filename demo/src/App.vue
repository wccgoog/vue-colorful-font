<template>
  <ColorfulFont :content="content" :fontSize="fontSize" />
</template>

<script>
import ColorfulFont from "vue-colorful-font";

export default {
  name: "App",
  components: {
    ColorfulFont,
  },
  data() {
    return {
      content: "wccccccccccccccccccccccccccccccccccccccccccccccccccccccc",
      fontSize: "100px",
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
