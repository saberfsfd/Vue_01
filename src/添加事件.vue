<template>
  <div>
<a @click="one" :href="url">点击去百度</a>
<hr>
<a @click="two(10,$event)" href="http://www.taobao.com">点击去淘宝</a>
  </div>
</template>

<script>
  export default {
   data(){
    return {
      url:"http://www.baidu.com"
    }
    },
    methods: {
      one(e){
        e.preventDefault()
      },
      two(num,e){
        e.preventDefault()
      }

    }
   
   
  }

</script>

<style lang="scss" scoped>

</style>