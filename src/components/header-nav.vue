<template>
  <div id='temp'>
    <h1>{{headerMsg}}</h1>
  </div>
</template>
<script>
export default{
  data () {
    return {
      headerMsg: 'hello world'
    }
  }
}
</script>
<style scoped>
  #temp{
    height: 100%;
    width: 100%;
    text-align: center;
  }
  #temp h1{
    color: #e9232c;
    font-size: 30px;
  }
</style>
