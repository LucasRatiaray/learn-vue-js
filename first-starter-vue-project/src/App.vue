<script setup>
import { ref } from 'vue'

const count = ref(0)
</script>

<template>

<button class="border-2 p-2" @click="count++">Click {{ count }}</button>

</template>

<style scoped>

</style>
