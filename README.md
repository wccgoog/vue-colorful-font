1. install
``` 
npm install vue-colorful-font
```
2. import the component
```
<template>
  <div>
    <ColorfulFont :content="content" :fontSize="fontSize" />
  </div>
</template>

<script>
import ColorfulFont from "vue-colorful-font";
export default {
  name: "About",
  components: {
    ColorfulFont,
  },
  data() {
    return {
      content: "wccccccccccccccccccccccccccccccccccccccccccccccccccccccc",
      fontSize: "100px",
    };
  },
  mounted() {},
};
</script>

<style>
</style>
```
3. the component accepts two props:
* content:whatever content you want to show us ~
* fontSize:literally what this prop's name means
