<template>
  <div >
    <div :class="className">haithem</div>

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
    return {
      num: 100,
      name: "haithem",
      country: ['tunis ', 'algeria'],
      verif: true,
      className: "fl"
    }
  },
  methods: {
    getName() {
      return this.name;
    },
  }


}
</script>

<style scoped>
.fl {
  font-size: 40px;
  color: red;
}
</style>
