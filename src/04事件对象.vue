<template>
  <div>
    <a @click="default1" href="http://www.baidu.com">阻止百度</a>
    <hr />
    <a @click="default2($event, 10)" href="http://www.baidu.com">阻止去百度</a>
  </div>
</template>

<script>
export default {
  methods: {
    default1(e) {
      e.preventDefault();
    },
    default2(e, num) {
      console.log(num);
      e.preventDefault();
    },
  },
};
</script>

<style></style>
