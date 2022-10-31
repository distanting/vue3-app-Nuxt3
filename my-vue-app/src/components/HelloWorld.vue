<script setup>
import { useMouse } from './../js/mouse.js'

const { x, y } = useMouse()
</script>

<template>Mouse position is at: {{ x }}, {{ y }}</template>


<style scoped>
.read-the-docs {
  color: #888;
}
</style>
