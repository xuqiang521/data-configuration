<template>
  <div id="app">
    <v-header></v-header>
    <v-content></v-content>
    <v-footer></v-footer>
  </div>
</template>

<script>
import VHeader from 'components/header'
import VContent from 'components/content'
import VFooter from 'components/footer'
export default {
  name: 'app',
  components: {
    VHeader,
    VContent,
    VFooter
  }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
