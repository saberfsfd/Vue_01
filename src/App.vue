<template>
  <div>
<div>
  <span>来自于:</span>

  <select v-model="from">
    <option value="北京市">北京</option>
    <option value="南京市">南京</option>
    <option value="天津市">天津</option>
  </select>
</div>
<div>
  <span>爱好:</span>
  <input type="checkbox" v-model="hobby" value="抽烟">抽烟
  <input type="checkbox" v-model="hobby"  value="喝酒">喝酒
  <input type="checkbox" v-model="hobby"  value="写代码">写代码
</div>
  </div>
</template>

<script>
  export default {
    data(){
      return {
        from:"",
        hobby:[]
      }
    }
  }
</script>

<style lang="scss" scoped>

</style>