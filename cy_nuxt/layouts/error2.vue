<template>
  <div class="container">
    <h1 >应用发生错误异常</h1>
    <nuxt-link to="/">首 页</nuxt-link>
    <Nuxt />
  </div>
</template>

<script>
export default {
  props: ['error'],
}
</script>
