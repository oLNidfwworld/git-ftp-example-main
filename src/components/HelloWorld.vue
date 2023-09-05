<script setup lang="ts">
interface Props {
  message: string;
}

const props = defineProps<Props>();
</script>

<template>
  <h1>{{ props.message }}</h1>

  <div class="card">
    <p>
      builded and deployed
    </p>
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
