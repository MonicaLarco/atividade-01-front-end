<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  
  <div class="content">
    <Header />
    <BlogList />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import BlogList from './components/BlogList.vue';

export default {
  name: "App",
  components: { Header, BlogList },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  font-size: 14px;
  /* margin-top: 60px; */
}
.content {
  max-width: 50%;
  margin: 40px auto;
  padding: 20px;
}

</style>
