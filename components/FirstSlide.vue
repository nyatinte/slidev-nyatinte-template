<script setup lang="ts">
const props = defineProps({
  /** タイトル */
  title: String,
  /** サブタイトル */
  subtitle: String,
  /** 所属 */
  belong: String,
});
</script>

<template>
  <div class="text-center justify-center">
    <h2>{{ title }}</h2>
    <h2>{{ subtitle }}</h2>
    <h3>{{ belong }}</h3>
  </div>
</template>
