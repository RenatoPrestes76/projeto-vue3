<template>
  <main>
    <Header />
    <CentralContainer
      myTitle1="Título diz: PÁGINA ABOUT"
      myText1="Texto da página about."
    />
    <Footer />
  </main>
</template>

<script>
import footer from '@/containers/footer/index.vue';
import headerHome from '@/containers/headerHome/index.vue';
import home from '@/containers/home/index.vue';
import login from '@/containers/login/index.vue';
import mainHome from '@/containers/mainHome/index.vue';
export default {
  name: 'About',
  components: {
    headerHome,
    footer,
    mainHome,
    login,
    home,
  },
};
</script>

<style lang="scss" scoped>
@import './index.scss';
</style>