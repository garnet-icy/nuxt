<template>
  <div>
    <h1>this is {{name}}</h1>
    <nuxt-link to="/user/12">传递12</nuxt-link>
  </div>
</template>
<script>
import firstLeaf from '../tree/firstLeaf'
export default {
  asyncData() {
    return {
      name: "user/index"
    };
  }
};
</script>
<style>
</style>
