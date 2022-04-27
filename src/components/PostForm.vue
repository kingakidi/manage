<template lang="">
  <div>
    <h2>Post Form</h2>
    <form @submit.prevent="postData">
      <input type="text" name="author" v-model="posts.author" /> <br />
      <input type="text" name="title" v-model="posts.title" /> <br />
      <button>Submit</button>
    </form>
  </div>
</template>
<script>
import  Vue from "vue"; // in Vue 3
import axios from "axios";
import VueAxios from "vue-axios";
export default {
  data() {
    return {
      posts: {
        title: null,
        author: null,
      },
    };
  },

  methods: {
    postData(e) {
      console.log(e);
      
    },
  },
};
</script>
<style lang=""></style>
