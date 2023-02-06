<template>
  <q-page class="flex flex-center">
    <p @click="increment()">Count: {{ count }}</p>
  </q-page>
</template>

<script setup>
import {ref} from 'vue'
const count = ref(0)
function increment() {
  count.value++
}
</script>
