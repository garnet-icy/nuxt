<template>
  <h1>this is {{name}}</h1>
</template>
<script>
export default {
  asyncData(){
    return {
      name:null,
    }
  },
  created(){
    this.name = this.$route.params.id
  }
}
</script>
<style>
</style>
