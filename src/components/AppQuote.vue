<script>
export default {
    name: 'AppQuote'
}
</script>
<template>
    <section class="quote">
        <div class="container quote-cont">
            <div class="quote-row text-white">
                <p>Our Home Owners Say</p>
                <div class="hrow">
                </div>
            </div>

        </div>
    </section>
</template>


<style lang="scss" scoped>
.quote {
    background-image: url('../assets/img/home-parallax-3.jpg');
    background-size: cover;
    background-position: center center;
    margin-top: 3rem;
    height: 1000px;
    margin: 0;
}

.quote-cont {
    padding-top: 12rem;
}

.quote-row p {
    font-size: 1.5rem;
    text-align: center;
}
</style>