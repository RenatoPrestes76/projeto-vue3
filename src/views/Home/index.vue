<template>
   <section>
    <home-Home />
    <home-mainHome />
    <home-footer />
  </section>
</template>

<script>
import Home from '@/containers/Home/index.vue';
import mainHome from '@/containers/MainHome/index.vue';
import footer from '@/containers/Footer/index.vue';
export default {
    name: 'home-page',
    componentes: {
        homeHome,
        homemainHome,
        homefooter,
    },
    
}:
</script>

<style scoped>
@import '@/views/Home/index.scss';
</style>