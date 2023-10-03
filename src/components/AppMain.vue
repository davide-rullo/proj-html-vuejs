<script>
import AppCta from './AppCta.vue';
import AppJumbo from './AppJumbo.vue';
import AppSpecialist from './AppSpecialist.vue';
import AppStats from './AppStats.vue';

export default {
    name: 'AppMain',
    components: { AppJumbo, AppCta, AppSpecialist, AppStats }
}
</script>
<template>
    <AppJumbo></AppJumbo>
    <AppCta></AppCta>
    <AppSpecialist></AppSpecialist>
    <AppStats></AppStats>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;
</style>