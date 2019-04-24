<template>
  <div id="home-page">
    <TheHeader />
    <Hero />
    <HeaderNav />
  </div>
</template>

<script>
import TheHeader from "~/components/TheHeader.vue";
import Hero from "~/components/Hero.vue";
import HeaderNav from "~/components/HeaderNav.vue";
export default {
  name: 'HomePage',
  components: {
    TheHeader,
    Hero,
    HeaderNav
  }
}
</script>

<style>
</style>
