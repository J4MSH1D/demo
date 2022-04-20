<script setup>
import { IonContent } from "@ionic/vue";
import { Swiper, SwiperSlide } from "swiper/vue";
import { EffectCoverflow } from "swiper"
import Title from "../components/Title.vue";
const modules = [EffectCoverflow]
</script>

<template>
<Title title="Speciall offer" />
    <div class="swiper">
      <Swiper
        :slides-per-view="1.3"
        :centeredSlides="true"
        loop
        :effect="'coverflow'"
        :modules="modules"
      >
        <SwiperSlide>
          <img src="@/assets/images/cs.jpg" alt="food" />
        </SwiperSlide>
        <SwiperSlide>
          <img src="@/assets/images/free.jpg" alt="food" />
        </SwiperSlide>
        <SwiperSlide>
          <img src="@/assets/images/p.jpg" alt="food" />
        </SwiperSlide>
        <SwiperSlide>
          <img src="@/assets/images/h.jpg" alt="food" />
        </SwiperSlide>
      </Swiper>
    </div>
</template>
