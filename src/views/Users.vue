<template>
  <div  v-for="(post,index) in posts" :key="index" >
    <p> {{ post.title }}</p>
  </div>
</template>

<script>
//
//import * as Vue from 'vue' // in Vue 3
import axios from 'axios'
//import VueAxios from 'vue-axios'


export default {
  name: `Users`,
  data() {
    return {
      posts: undefined
    }
  },
  mounted() {
    axios.get('https://jsonplaceholder.typicode.com/posts').then(response => {
      this.posts = response.data;
      console.log(this.posts);
    });

  }
}
</script>

<style scoped>

</style>