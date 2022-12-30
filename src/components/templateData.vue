<!-- 模板字符 -->
<template>
  <div class='templateData'>
    <input type="text" v-model="value">
    <div>{{value}}</div>
  </div>
</template>

<script setup  lang='ts'>
  import { ref } from 'vue'
  const value = ref('text')
</script>
<style lang='scss'>
</style>
