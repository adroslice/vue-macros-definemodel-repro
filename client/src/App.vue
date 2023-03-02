<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'

let test = $ref("Testing 123")
</script>

<template>
  <HelloWorld v-model="test" />
</template>

<style scoped>
</style>
