<template>
  <q-page class="flex container">
    <h1>Bored?</h1>
  </q-page>
</template>

<script setup>
import { defineProps, reactive } from 'vue'

const data = {
  msg: {
    type: String,
    default: " "
  }
}

const state = reactive({ count: 0 })
</script>

<style scoped>
</style>