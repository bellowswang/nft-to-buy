<script setup>
import { ref } from 'vue';

defineProps({
  msg: String,
});

const count = ref(0);
</script>

<template>
  <h1>{{ msg }}</h1>

  <p>
    by
    <a href="https://twitter.com/mondoaxi" target="_blank">daNFTpeng</a>
  </p>

  <button type="button" @click="count++">Search</button>
</template>

<style scoped>
a {
  color: #42b983;
}
</style>
