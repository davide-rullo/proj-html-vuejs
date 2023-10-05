<script>
import AppFooter from './components/AppFooter.vue';
import AppMain from './components/AppMain.vue';
import SiteHeader from './components/SiteHeader.vue';


export default {
  name: 'App',
  data() {
    return {
      items: [
        {
          name: 'Home'
        },
        {
          name: 'About'
        },
        {
          name: 'Services'
        },
        {
          name: 'Work'
        },
        {
          name: 'Articles'
        },
      ]
    };
  },
  components: { AppMain, AppFooter, SiteHeader }
}
</script>

<template>
  <SiteHeader :items="items"></SiteHeader>
  <AppMain></AppMain>
  <AppFooter></AppFooter>
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

.others {
  padding-top: 5rem;
}

.others p {
  margin: 0;
}

.others-hr {
  width: 15vw;
  margin: auto;
  height: 1px;
  background-color: rgba(0, 0, 0, 0.185);
}
</style>
