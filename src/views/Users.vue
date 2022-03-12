<template>
  <div>
    <h1> this is users page </h1>
    <h1> user name {{ $route.params.name }}</h1>
  </div>
</template>

<script>
//
import * as Vue from 'vue' // in Vue 3
import axios from 'axios'
import VueAxios from 'vue-axios'




export default {
  name: `Users`
}
</script>

<style scoped>

</style>