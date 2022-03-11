<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <h1>welcome haithem</h1>

  <First msg="vue3 " > </First>
</template>

<script>
import First from "@/components/First";
import Second from "@/components/Second";
export default {
  name: 'App',
  components: {
    First ,
    Second
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
