<script>
import AppHeader from './components/AppHeader.vue';

export default {
  name: 'App',
  data() {
    return {};
  },
  components: { AppHeader }
}
</script>

<template>
  <AppHeader></AppHeader>
</template>

<style lang="scss">
@use './assets/scss/partials/variables.scss' as *;

body {
  font-family: 'Montserrat', sans-serif;
}

img {
  max-width: 100%;
}
</style>
