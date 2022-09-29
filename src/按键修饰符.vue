<template>
  <div>
<input type="text" @keydown.enter="enterFn">
<hr>
<input type="text" @keydown.esc="escFn">
  </div>
</template>

<script>
  export default {
    data(){
return {
  
}
    },
    methods:{
      enterFn(){
console.log("用户按下的回车");
      },
      escFn(){
        console.log("用户按下esc键");
      }
    }
  }
</script>

<style lang="scss" scoped>

</style>