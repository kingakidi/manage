<template>
  <div id="app"><PostForm /></div>
</template>

<script>
import PostForm from "./components/PostForm.vue";
export default {
  name: "App",
  components: {
    PostForm,
  },cd 
};
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
