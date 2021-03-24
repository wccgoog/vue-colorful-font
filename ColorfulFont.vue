<template>
  <div class="colorful" :style="style" style="-webkit-background-clip: text">
    {{ content }}
  </div>
</template>

<script>
export default {
  name: "ColorfulFont",
  props: {
    content: String,
    fontSize: String,
  },
  data() {
    return {
      style: {
        //   设置背景颜色渐变
        background:
          "linear-gradient(90deg,#03a9f4,#ffeb3b,#f441a5,#ff253a,#bbffaa,#EEEEEE)",
        //   设置背景填充比例,放大4倍,使颜色过渡柔和,淡化线条
        backgroundSize: "400%",
        fontSize: this.fontSize,
      },
    };
  },
};
</script>

<style>
@keyframes stream {
  from,
  to {
    background-position: 0%; /*无线循环,开始和结束帧设置相同*/
  }
  50% {
    background-position: 100%; /*关键帧设置背景移动100%*/
  }
}
.colorful {
  /* background-size: 400%; */
  animation: stream 8s infinite linear; /*开启动画帧,线性移动背景,无限循环*/
  background-clip: text;
  -webkit-text-fill-color: transparent;
}
</style>