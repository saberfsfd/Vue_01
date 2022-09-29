<template>
  <div>
<p>你要购买的物品{{count}}</p>
<button v-on:click="count=count+1">+1</button>
<button v-on:click="addFn">+1</button>
<button @click="addCountFn(5)">+5</button>
  </div>
</template>

<script>
  export default {
   data(){
    return {
      count:1,
    }
   },
   methods:{
    addFn(){
      this.count++
    },
    addCountFn(num){
      this.count=this.count+num
    }
   }
  }

</script>

<style lang="scss" scoped>

</style>