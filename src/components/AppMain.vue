<script>
import AppCta from './AppCta.vue';
import AppJumbo from './AppJumbo.vue';
import AppSpecialist from './AppSpecialist.vue';

export default {
    name: 'AppMain',
    components: { AppJumbo, AppCta, AppSpecialist }
}
</script>
<template>
    <AppJumbo></AppJumbo>
    <AppCta></AppCta>
    <AppSpecialist></AppSpecialist>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;
</style>