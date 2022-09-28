<template>
  <Page :data="data"/>
</template>

<script>
import data from './data.json'
import Page from './components/Page.vue'

export default {
  name: 'App',
  components: {
    Page,
  },
  data() {
    return {
      data: data
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
