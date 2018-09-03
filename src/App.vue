<template>
  <div id="app">
    <router-view/>
    <Header></Header>
  </div>
</template>
<script>
import Header from './components/Header.vue';
export default {
  name: 'App',
  components: {
    Header,
  }
}
</script>
<style>
* {
  padding: 0;
  margin: 0;
}
</style>
