<template>
  <div id="app">
    <hero-component />
    <services-component />
    <footer-component />
  </div>
</template>

<script>
import HeroComponent from './components/HeroComponent.vue';
import ServicesComponent from './components/ServicesComponent.vue';
import FooterComponent from './components/FooterComponent.vue';

export default {
  name: 'App',
  components: {
    HeroComponent,
    ServicesComponent,
    FooterComponent,
  },
};
</script>

<style lang="scss">
@import "src/scss/custom";
</style>
