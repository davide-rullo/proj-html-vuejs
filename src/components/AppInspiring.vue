<script>
export default {
    name: 'AppInspiring'
}
</script>
<template>
    <section class="inspiring">
        <div class="container">
            <div class="row">
                <div class="col-12 col-sm-8">
                    <div class="inspiring-row">
                        <p>Building Inspiring Spaces</p>
                        <div class="divide">
                        </div>
                        <div class="inspiring-subtitle pt-4 pb-5">
                            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quia cupiditate molestias aut,
                                quibusdam
                            </p>
                        </div>
                    </div>
                </div>
                <div class="col-12 col-sm-4 ">
                    <div class="yellow-btn justify-content-center">
                        <button>GET A FREE QUOTE</button>

                    </div>
                    <div class="inspiring-subtitle text-center pt-4 pb-5">
                        <p>Only takes a few seconds!
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;

.inspiring {
    height: 700px;
    background-image: url('../assets/img/about-call-to-action-57862405.jpg');
    background-size: cover;
    color: white;
    display: flex;
    align-items: center;
}

.inspiring-row p {
    font-size: 1.5rem;
}

.divide {
    width: 15vw;
    height: 1px;
    background-color: $avd-primary ;
}

.inspiring-subtitle p {
    font-size: 1rem;
}

.yellow-btn {
    display: flex;

}

.yellow-btn button {
    border: none;
    text-align: center;
    background-color: $avd-primary;
    color: #000000A6;
    padding: 1rem 2rem;
}

.yellow-btn button:hover {
    background-color: $avd-lightDark;
    color: $avd-white;
    transition: all .3s linear;
}
</style>