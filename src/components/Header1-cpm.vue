<template>
  <div id="header">
    <h2>{{ text1 }}</h2>
    <h1>{{ text2 }}</h1>
  </div>
</template>
<script>
export default {
  name: 'Header1',
  props: {
    text: {
      type: String,
    },
  },
};
</script>
<style></style>
