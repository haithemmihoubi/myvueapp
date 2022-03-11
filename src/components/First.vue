<template>
  <div>
    <h1>haithem</h1>
    <p>{{ num }}</p>
    <p>{{ name }}</p>
    <p> get name function {{ getName()  }}</p>
    <p v-for=" c in country">{{ c }}</p>
  </div>
</template>

<script>

export default {
  name: "First",
  components: {},
 /* props: {
    msg: String,
    phone: Number
  },*/
  data() {
    return  {
      num:100 ,
      name:"haithem",
      country:['tunis ','algeria'] ,
      verif:true
    }
  },
 methods: {
    getName(n) {
      return this.n;
    },
 }


}
</script>

<style scoped>
h1 {
  color: cornflowerblue;
  font-size: 20px;
}
</style>
