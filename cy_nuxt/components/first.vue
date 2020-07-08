<template>
  <h1 class="red">this is {{ name }}</h1>
</template>

<script>

export default {
  data(context){
    return {
      name:'首页',
    }
  }
}
</script>

<style>
.red {
  color: red;
}
</style>
