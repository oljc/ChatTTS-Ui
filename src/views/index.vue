<script setup lang="ts">
defineOptions({
  name: 'HomeView'
});
</script>

<template>
  <main>
    <a-textarea
      style="width: 500px"
      placeholder="Please enter something"
      allow-clear
      show-word-limit
      :max-length="{ length: 300, errorOnly: true }"
    />
  </main>
</template>
