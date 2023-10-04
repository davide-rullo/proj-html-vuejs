        
<script>
export default {
    name: 'AppWork'
}
</script>
<template>
    <section class="works">
        <div class="container">
            <div class="work-row">
                <p>Explore Recent Work</p>
                <div class="hrow">
                </div>
                <div class="work-subtitle text-center pt-4 pb-5">
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe architecto consectetur quis corrupti
                        quas.
                        Illo, magnam?</p>
                </div>
            </div>
            <div class="row row-cols-1 row-cols-sm-3">
                <div class="col p-2">
                    <div class="card-work">
                        <img src="../assets/img/project1-featured-294276386-400x400.jpg" alt="">
                    </div>
                </div>
                <div class="col p-2">
                    <div class="card-work">
                        <img src="../assets/img/project2-featured-15013609-400x400.jpg" alt="">
                    </div>
                </div>
                <div class="col p-2">
                    <div class="card-work">
                        <img src="../assets/img/project3-featured-189023420-400x400.jpg" alt="">
                    </div>
                </div>
            </div>
            <div class="others d-flex justify-content-center align-items-center">
                <div class="others-hr">

                </div>
                <p>VIEW ALL PROJECTS</p>
                <div class="others-hr">

                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;



.work-row p {
    font-size: 1.5rem;
    text-align: center;
}

.work-subtitle p {
    font-size: .9rem;
}



.card-work {
    display: flex;
    justify-content: center;
}
</style>