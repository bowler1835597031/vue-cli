<template>
  <div>
    <input type="text" v-model="val" />
    <br />
    <input type="password" v-model="val1" @input="inputFn" />
  </div>
</template>

<script>
export default {
  data() {
    return {
      val: '',
      val1: '',
    };
  },
  methods: {
    inputFn(e) {
      this.val1 = e.target.value;
    },
  },
};
</script>
