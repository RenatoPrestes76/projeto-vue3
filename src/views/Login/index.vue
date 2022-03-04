<template>
  <div>
    <login></login>
  </div>
</template>

<script>
import Login from '@/containers/Login/index.vue';
export default {
  name: 'Login-page',
  components: {
    Login,
 
  },
};
</script>

<style lang="scss" scoped>
@import '@/views/Login/index.scss';
</style>
