<template>
   <section>
    <Home-page />
    <mainHome-page />
    <footer-page />
  </section>
</template>

<script>
import Home from '@/containers/Home/index.vue';
import mainHome from '@/containers/MainHome/index.vue';
import footer from '@/containers/Footer/index.vue';
export default {
    name: 'home-page',
    componentes: {
        Home,
        mainHome,
        footer,
    },
    
}
</script>

<style scoped>
@import '@/views/Home/index.scss';
</style>