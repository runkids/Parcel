<template>
  <div class="container">
      <h1><p id='text'>{{text}}</p></h1>
  </div>
</template>
<script>
export default {
  data(){
    return{
      text: 'Hello World !',
    }
  },
  watch:{
  }
}
</script>
<style lang="scss" scoped>
h1{
  color: royalblue;
}
</style>