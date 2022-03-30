<template>
  <div id="form1">
    <label for="name">{{ name }}</label>
    <input type="text" id="foobar" placeholder="Foo Bar" />
  </div>
</template>
<script>
export default {
  name: 'Form1',
  props: {
    text: {
      type: String,
    },
  },
};
</script>
<style scoped></style>
