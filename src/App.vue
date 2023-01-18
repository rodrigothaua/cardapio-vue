<template>
  <Header />
</template>

<script>

import Header from './components/Header.vue';

export default {
  name: "index",
  components: {
    Header
  }
}
</script>

<style>
  *{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    -webkit-tap-highlight-color: transparent;
    color: rgb(27, 28, 30);
  }

  body{
    -webkit-font-smoothing: antialiased;
    color: rgb(27, 28, 30);
    background: f1f1f1;
  }
</style>