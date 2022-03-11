<template>
  <div>
    <div>{{ salary }}</div>
    <input type="text" name="salary" id="sal" v-model="salary" @keyup.enter="increment()">

  </div>
</template>

<script>

export default {
  name: "First",

  data() {
    return {
      salary: 1
    }
  },

  methods: {
    increment() {
      this.salary += 100;
    }
  }


}
</script>

<style scoped>
.fl {
  font-size: 40px;
  color: red;
}
</style>
