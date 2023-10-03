<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/appMain.vue';


export default {
  name: 'App',
  data() {
    return {};
  },
  components: { AppHeader, AppMain }
}
</script>

<template>
  <AppHeader></AppHeader>
  <AppMain></AppMain>
</template>

<style lang="scss">
@use './assets/scss/partials/variables.scss' as *;

body {
  font-family: 'Montserrat', sans-serif;
}

img {
  max-width: 100%;
}

.hrow {
  width: 15vw;
  margin: auto;
  height: 1px;
  background-color: $avd-primary ;
}
</style>
