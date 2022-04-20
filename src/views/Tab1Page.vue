<script setup>
import NameOftab from "../components/NameOftab.vue";
import Swiper from "../components/Swiper.vue";
import FastDelivering from "../components/FastDelivering.vue";
import { IonPage, IonContent } from "@ionic/vue";
</script>

<template>
  <IonPage>
    <IonContent>
      <NameOftab name="Home" />
      <Swiper />
      <FastDelivering />
    </IonContent>
  </IonPage>
</template>
