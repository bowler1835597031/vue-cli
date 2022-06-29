<template>
  <div>
    <a v-bind:href="url">点我即可进入百度</a>
    <img :src="imgUrl" alt="" />
    <img :src="localImg" alt="" />
  </div>
</template>

<script>
import localImg from './assets/logo.png';
export default {
  data() {
    return {
      url: 'http://www.baidu.com',
      imgUrl:
        'http://yun.itheima.com/Upload/./Images/20210412/60741c11ab77b.jpg',
      localImg,
    };
  },
};
</script>

<style></style>
