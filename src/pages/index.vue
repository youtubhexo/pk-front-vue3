<template>
  <div>
    <div class="m-4 shadow-md">hello-world 今天日期：{{ new Date().toLocaleDateString() }}</div>
    <h1 class="text-3xl font-bold underline">Hello world!</h1>
    {{ msg }}
  </div>
</template>

<script setup>
const msg = ref('desperado blog')
</script>

<style lang="scss" scoped></style>
