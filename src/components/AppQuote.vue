<script>
export default {
    name: 'AppQuote',
    data() {
        return {

        }
    },
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
            <div class="customer d-flex justify-content-center flex-column align-items-center gap-4 pt-4">


                <img src="../assets/img/home-testimonial-113165296.jpg" alt="">
                <p><i>“No man but feels more of a man in the world if he have but a bit of ground that he can call his own.
                        However small it is on the surface, it is four thousand miles deep; and that is a very handsome
                        property.”</i></p>
                <h6 style="font-weight: 700;">HARRY SMITH, NEW HOME OWNER</h6>

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



img {
    border-radius: 50%;
    width: 200px;
}

.customer {
    color: white;
    text-align: center;
    width: 60%;
    margin: auto;
}
</style>