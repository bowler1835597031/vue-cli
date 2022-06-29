<template>
  <div>
    <h1>{{ msg }}</h1>
    <button @click="btn">翻转世界</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      msg: 'Helllo,World',
    };
  },
  methods: {
    btn() {
      this.msg = this.msg.split('').reverse().join('');
    },
  },
};
</script>

<style></style>
