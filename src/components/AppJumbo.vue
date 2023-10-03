<script>
export default {
    name: 'Appjumbo'
}
</script>
<template>
    <section class="jumbo">
        <div class="pop d-flex flex-column align-items-end p-2">
            <div class="demos d-flex justify-content-center align-items-center mb-2">

                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-stack"
                    viewBox="0 0 16 16">
                    <path
                        d="m14.12 10.163 1.715.858c.22.11.22.424 0 .534L8.267 15.34a.598.598 0 0 1-.534 0L.165 11.555a.299.299 0 0 1 0-.534l1.716-.858 5.317 2.659c.505.252 1.1.252 1.604 0l5.317-2.66zM7.733.063a.598.598 0 0 1 .534 0l7.568 3.784a.3.3 0 0 1 0 .535L8.267 8.165a.598.598 0 0 1-.534 0L.165 4.382a.299.299 0 0 1 0-.535L7.733.063z" />
                    <path
                        d="m14.12 6.576 1.715.858c.22.11.22.424 0 .534l-7.568 3.784a.598.598 0 0 1-.534 0L.165 7.968a.299.299 0 0 1 0-.534l1.716-.858 5.317 2.659c.505.252 1.1.252 1.604 0l5.317-2.659z" />
                </svg>
                <p>Demos</p>
            </div>
            <div class="sale justify-content-center align-items-center">

            </div>
        </div>
        <div class="container jumbo-wrap d-flex justify-content-center align-items-center flex-column gap-2">
            <div class="catch text-white">
                <h1 class="fw-bold">BUILDING INSPIRING SPACES </h1>
            </div>
            <div class="subtitle">
                <h6>We Build Inspiring Residential And Commercial Spaces </h6>
            </div>
            <div class="cta d-flex gap-3">
                <button class="dark-btn">EXPLORE RECENT WORK</button>
                <button class="yellow-btn">GET A QUOTE TODAY</button>
            </div>
        </div>
    </section>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;

.jumbo {
    background-image: url('../assets/img/home-slider.jpg');
    background-size: cover;
    background-repeat: no-repeat;
}

.jumbo-wrap {
    padding: 18rem;
}

.subtitle {
    color: $avd-primary;
}

.cta button {
    padding: .5rem 2rem;
    border: none;
}

.dark-btn {
    background-color: $avd-lightDark;
    color: white;
}

.yellow-btn {
    background-color: $avd-primary;
}

.demos,
.sale {
    width: 3rem;
    aspect-ratio: 1/1;
    background-color: white;
    border-radius: 4px;
}
</style>