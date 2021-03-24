1. 安装
``` 
npm install vue-colorful-font
```
2. 引入组件
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
3. 组件接收两个参数:
* content:希望展示的任何文字 ~
* fontSize:字体大小




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
