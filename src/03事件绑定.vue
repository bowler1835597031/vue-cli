<template>
  <div>
    <p>你要购买商品的数量: {{ count }}</p>
    <button v-on:click="count += 1">+1</button>
    <button @click="addFn">+1</button>
    <button @click="addFn1(5)">+5</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      count: 0,
    };
  },
  methods: {
    addFn() {
      this.count++;
    },
    addFn1(value) {
      console.log(value);
      this.count = this.count + value;
    },
  },
};
</script>

<style></style>
