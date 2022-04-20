<script setup>
import { IonItem, IonHeader } from "@ionic/vue";
defineProps({
  name: {
    required: true,
    type: String,
  },
});
</script>

<template>
  <IonHeader>
    <div class="navbar">
      {{ name }}
    </div>
  </IonHeader>
</template>
