<script>
import AppCta from './AppCta.vue';
import AppJumbo from './AppJumbo.vue';
import AppSpecialist from './AppSpecialist.vue';
import AppStats from './AppStats.vue';
import AppWork from './AppWork.vue';

export default {
    name: 'AppMain',
    components: { AppJumbo, AppCta, AppSpecialist, AppStats, AppWork }
}
</script>
<template>
    <AppJumbo></AppJumbo>
    <AppCta></AppCta>
    <AppSpecialist></AppSpecialist>
    <AppStats></AppStats>
    <AppWork></AppWork>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;
</style>