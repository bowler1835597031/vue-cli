<template>
  <div>
    <div>
      <span>用户名:</span>
      <input type="text" v-model.number="phone" />
    </div>
    <div>
      <span>密码:</span>
      <input type="password" v-model.trim="message" />
    </div>
    <br />
    <textarea id="" cols="30" rows="10" v-model.lazy="info"></textarea>
  </div>
</template>

<script>
export default {
  data() {
    return {
      phone: '',
      message: '',
      info: '',
    };
  },
};
</script>

<style></style>
