<script>
export default {
    name: 'AppCta'
}
</script>
<template>
    <section class="cta">
        <div class="cta-wrapper container d-flex justify-content-center align-items-center flex-column">
            <p class="cta-text">Do You Have A Construction Project We Can Help With ?</p>
            <div class="btn-wrap">
                <button class="cta-btn ">
                    GET A FREE QUOTE
                </button>
            </div>
        </div>

    </section>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;

.cta {
    background-color: $avd-primary;
}

.cta-wrapper {

    padding: 2rem;

    p {
        margin: 0;
        font-size: 1.5rem;
    }
}

.btn-wrap {
    margin-bottom: -3rem;
    margin-top: 2rem;
}

.cta-btn {
    background-color: $avd-lightDark;
    border: 1px solid white;
    color: white;
    padding: .3rem 1rem;
    letter-spacing: 3px;

}

.cta-btn:hover {
    background-color: $avd-white;
    color: $avd-lightDark;
    border: 1px solid black;
}
</style>