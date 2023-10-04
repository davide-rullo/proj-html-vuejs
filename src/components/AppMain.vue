<script>
import AppCta from './AppCta.vue';
import AppJumbo from './AppJumbo.vue';
import AppQuote from './AppQuote.vue';
import AppSpecialist from './AppSpecialist.vue';
import AppStats from './AppStats.vue';
import AppValues from './AppValues.vue';
import AppWork from './AppWork.vue';

export default {
    name: 'AppMain',
    components: { AppJumbo, AppCta, AppSpecialist, AppStats, AppWork, AppValues, AppQuote }
}
</script>
<template>
    <AppJumbo></AppJumbo>
    <AppCta></AppCta>
    <AppSpecialist></AppSpecialist>
    <AppStats></AppStats>
    <AppWork></AppWork>
    <AppValues></AppValues>
    <AppQuote></AppQuote>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;
</style>