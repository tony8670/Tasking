<script setup>
import Navbar from "./components/Navbar.vue";
import HeroSection from "./components/HeroSection.vue";
</script>

<template>
  <div class="content">
    <Navbar/>
    <HeroSection/>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;700&display=swap');
*{
  font-family: 'Poppins',sans-serif;
}
.content {
  padding: 1.2rem 10rem;

}
</style>
