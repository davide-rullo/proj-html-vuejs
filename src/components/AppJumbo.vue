<script>
export default {
    name: 'Appjumbo'
}
</script>
<template>
    <section class="jumbo">
        <div class="pop d-flex flex-column align-items-end p-2">
            <a href="#">
                <div class="demos d-flex flex-column justify-content-center align-items-center mb-2 gap-1">

                    <svg xmlns="http://www.w3.org/2000/svg" height="1.2em"
                        viewBox="0 0 576 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                        <path
                            d="M264.5 5.2c14.9-6.9 32.1-6.9 47 0l218.6 101c8.5 3.9 13.9 12.4 13.9 21.8s-5.4 17.9-13.9 21.8l-218.6 101c-14.9 6.9-32.1 6.9-47 0L45.9 149.8C37.4 145.8 32 137.3 32 128s5.4-17.9 13.9-21.8L264.5 5.2zM476.9 209.6l53.2 24.6c8.5 3.9 13.9 12.4 13.9 21.8s-5.4 17.9-13.9 21.8l-218.6 101c-14.9 6.9-32.1 6.9-47 0L45.9 277.8C37.4 273.8 32 265.3 32 256s5.4-17.9 13.9-21.8l53.2-24.6 152 70.2c23.4 10.8 50.4 10.8 73.8 0l152-70.2zm-152 198.2l152-70.2 53.2 24.6c8.5 3.9 13.9 12.4 13.9 21.8s-5.4 17.9-13.9 21.8l-218.6 101c-14.9 6.9-32.1 6.9-47 0L45.9 405.8C37.4 401.8 32 393.3 32 384s5.4-17.9 13.9-21.8l53.2-24.6 152 70.2c23.4 10.8 50.4 10.8 73.8 0z" />
                    </svg>
                    <h6>Demos</h6>
                </div>
            </a>
            <a href="#">
                <div class="sale d-flex flex-column justify-content-center align-items-center">
                    <div class="sale-price d-flex">
                        <h6 style="padding-bottom: .7rem;">$</h6>
                        <h4>39</h4>
                    </div>
                    <div class="sale-title">
                        <h6>On Sale</h6>
                    </div>
                </div>
            </a>
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

a {
    text-decoration: none;
    color: black;
}

.demos h6,
.sale h6,
.sale h4 {
    margin: 0;
}

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

.demos h6,
.sale h6 {
    font-size: .6rem;
    font-weight: 600;
}

.sale h6 {}

.sale h4 {
    font-weight: 700;
}

.sale-price {
    color: #65BC7B;
}

svg {
    fill: #33475B;
}
</style>