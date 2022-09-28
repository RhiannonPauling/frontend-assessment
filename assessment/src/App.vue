<template>
  <div>
    <Banner />
    <Content />
  </div>
</template>

<script>
import Content from './components/Content.vue';
import Banner from './components/Banner.vue';

export default {
  name: 'App',
  components: {
    Content,
    Banner
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
