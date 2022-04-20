<script setup>
defineProps({
  title: {
    required: true,
    type: String,
  },
});
</script>
<template>
  <div class="title">
    {{ title }}
  </div>
</template>
