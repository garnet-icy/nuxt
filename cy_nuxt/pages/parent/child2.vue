<template>
<div>
  <h1>子组件{{name}}</h1>
</div>
</template>
<script>
export default {
  asyncData(){
    return {
      name:"child2",
    }
  }
}
</script>
<style>
</style>
