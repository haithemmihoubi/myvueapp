<template>
  <div>
    <div>haithem</div>
    <h5>{{ salary }}</h5>
    <button v-on:click="incrementSalary()">incrementSalary</button>
    <button v-on:click="decrementSalary()">decrementSalary</button>
    <button v-on:click="resetSalary()">resetSalary</button>
  </div>
</template>

<script>

export default {
  name: "First",

  data() {
    return {
      salary: 500

    }
  },

  methods: {
    incrementSalary() {
      this.salary += 100;
    }, decrementSalary() {
      this.salary -= 100;
    },
    resetSalary() {
      this.salary = 0.00;
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
