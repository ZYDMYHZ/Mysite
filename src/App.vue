<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
  <div>
    <h1>Hello, Vue!</h1>
    <p>欢迎来到我的 Vue 页面。</p>
    <RouterLink to="/">返回首页</RouterLink>
  </div>
</template>

<style scoped>
h1 {
  color: #42b983;
}
p {
  font-size: 16px;
}
</style>
