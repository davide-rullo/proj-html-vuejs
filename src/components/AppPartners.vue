<script>
export default {
    name: 'AppPartners'
}
</script>
<template>
    <section class="partners pt-5 pb-5">
        <div class="container ">
            <div class="partners-row">
                <p>Trusted Partners</p>
                <div class="hrow">
                </div>
                <div class="partners-subtitle text-center pt-4 pb-5">
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe architecto consectetur quis corrupti
                        quas.
                        Illo, magnam?</p>
                </div>
            </div>
            <div class="row row-cols-1 row-cols-sm-3 row-cols-md-5">
                <div class="col p-2">
                    <div class="company">
                        <a href="#"><img src="../assets/img/home-logo11-219096700-320x202.png" alt=""></a>
                    </div>
                </div>
                <div class="col p-2">
                    <div class="company">
                        <a href="#"><img src="../assets/img/home-logo10-219096700-320x202.png" alt=""></a>
                    </div>
                </div>
                <div class="col p-2">
                    <div class="company">
                        <a href="#"><img src="../assets/img/home-logo2-219096700-320x202.png" alt=""></a>
                    </div>
                </div>
                <div class="col p-2">
                    <div class="company">
                        <a href="#"><img src="../assets/img/home-logo1-219096700-320x202.png" alt=""></a>
                    </div>
                </div>
                <div class="col p-2">
                    <div class="company">
                        <a href="#"><img src="../assets/img/home-logo9-219096700-320x202.png" alt=""></a>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>


<style lang="scss" scoped>
.partners-row p {
    font-size: 1.5rem;
    text-align: center;
}

.partners-subtitle p {
    font-size: .9rem;
}

.company {
    display: flex;
    justify-content: center;
}
</style>