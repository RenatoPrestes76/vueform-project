<template>
  <main>
    <head>
      <Header1 h2="Form" />
      <Header1 h1="First Tab" />
    </head>
    <content>
      <Form1 name="Full Name *" input />
    </content>
  </main>
</template>
<script>
import Header1 from '@/components/Header1-cpm.vue';
import Form1 from '@/components/Form1-cpm.vue';

export default {
  name: 'App',
  components: {
    Header1,
    Form1,
  },
};
</script>

<style></style>
