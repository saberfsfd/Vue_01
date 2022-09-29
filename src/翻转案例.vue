<template>
  <div>
<h1>{{msg}}</h1>
<button @click="reverseFn">
  翻转世界
</button>
  </div>
</template>

<script>
  export default {
    data(){
      return {
msg:"Hello,World"
      }
    },methods:{
      reverseFn(){
        this.msg =this.msg.split("").reverse().join('')
      }
    }
  }
</script>

<style lang="scss" scoped>

</style>