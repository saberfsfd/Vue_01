<template>
  <div>
<h1>{{msg}}</h1>
<h2>{{obj.name}}</h2>
<h3>{{obj.name>=18? '成年了':"没"}}</h3>
  </div>
</template>

<script>
  export default {
    data(){
return{
  msg:'Hello,Vue',
  obj:{
    name:'小vue',
    age:5
  }
}


    }
  }
</script>

<style lang="scss" scoped>

</style>