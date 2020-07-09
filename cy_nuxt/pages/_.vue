<template>
  <div>
    <h1>404页面</h1>
  </div>
</template>
<script>
export default {
  asyncData(){
    return {
      error:{
        statusCode:401,
      }
    }
  },
  // layout:'error',
  layout (context) {
    return 'error2'
  }
}
</script>
