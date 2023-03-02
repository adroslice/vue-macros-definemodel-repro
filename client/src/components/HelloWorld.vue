<script setup lang="ts">
let { modelValue } = $defineModel<{
  modelValue: string
}>()

watch($$(modelValue), () => console.log(modelValue))
</script>

<template>
  <input v-model="modelValue"/>
</template>
