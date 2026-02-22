<template>
  <div>
    <Header />
    <Hero />
    <Services />
    <About />
  </div>
</template>
<script setup>
import { onMounted } from "vue";
import Header from "@components/Header.vue";
import Hero from "@components/Hero.vue";
import AOS from "aos";
import Services from "@components/Services.vue";
import "aos/dist/aos.css";
import About from "@components/About.vue";

onMounted(() => {
  AOS.init();
});
</script>
