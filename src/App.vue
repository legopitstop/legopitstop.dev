<template>
  <ComingSoon />
  <FooterBar />
</template>

<script>
import ComingSoon from './components/ComingSoon.vue'
import FooterBar from './components/FooterBar.vue'

export default {
  name: 'App',
  components: {
    ComingSoon,
    FooterBar
  }
}
</script>

<style>
:root {
  background-color: #1f1f1f;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
  margin-top: 60px;
}
</style>./components/Temp.vue
