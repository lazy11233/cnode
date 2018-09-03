<template>
  <div id="app">
    <Header></Header>
    <div class="main">
    <PostList></PostList>

    </div>
  </div>
</template>
<script>
import Header from './components/Header.vue';
import PostList from './components/PostList.vue';
export default {
  name: 'App',
  components: {
    Header,
    PostList
  }
}
</script>
<style>
* {
  padding: 0;
  margin: 0;
}
ul,li {
  list-style: none;
}
.main {
  width: 80%;
  margin: 0 auto;
}
</style>
