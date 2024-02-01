# css3实现彩色动画字体
1. 安装
``` 
npm install vue-colorful-font
```
2. 引入组件
```
<script setup lang="ts">
import ColorfulFont from "vue-colorful-font";
import { ref, onMounted } from "vue";
const fontSize = ref('96px')
const content = ref('wcccccccccccccccccccccccccccccccccc')
onMounted(() => { });
</script>

<template>
  <ColorfulFont :content="content" :fontSize="fontSize" />
</template>

<style scoped></style>

```
3. 组件接收两个参数:
* content:希望展示的任何文字 ~
* fontSize:字体大小



# based on css3,colorful animate font
1. install
``` 
npm install vue-colorful-font
```
2. import the component
```
<script setup lang="ts">
import ColorfulFont from "vue-colorful-font";
import { ref, onMounted } from "vue";
const fontSize = ref('96px')
const content = ref('wcccccccccccccccccccccccccccccccccc')
onMounted(() => { });
</script>

<template>
  <ColorfulFont :content="content" :fontSize="fontSize" />
</template>

<style scoped></style>

```
3. the component accepts two props:
* content:whatever content you want to show us ~
* fontSize:literally what this prop's name means
