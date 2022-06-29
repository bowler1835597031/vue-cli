<template>
  <div>
    <input type="text" @keydown.enter="enterFn" />
    <hr />
    <input type="text" @keydown.delete="deleteFn" />
  </div>
</template>

<script>
export default {
  methods: {
    enterFn() {
      alert('enter');
    },
    deleteFn() {
      alert('delete');
    },
  },
};
</script>

<style></style>
