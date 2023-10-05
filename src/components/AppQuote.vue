
<script>
import image from '../assets/img/home-testimonial-113165296.jpg';
import imageJohn from '../assets/img/home-testimonial-84268399.jpg';

export default {
    name: 'AppQuote',
    data() {
        return {
            activeImage: 0,
            slides: [
                {
                    image: image,
                    quote: 'No man but feels more of a man in the world if he have but a bit of ground that he can call his own.However small it is on the surface, it is four thousand miles deep; and that is a very handsomeproperty.',
                    name: 'HARRY SMITH, NEW HOME OWNER'
                }, {
                    image: imageJohn,
                    quote: 'Many novice real estate investors soon quit the profession and invest. When you invest in real estate, you often see a side of humanity that stocks, bonds, mutual funds, and saving money shelter you from.',
                    name: 'JOHN DOE • PROPERTY INVESTOR'
                },
            ]
        }
    },

    methods: {

        next() {
            this.activeImage++
            if (this.activeImage > this.slides.length - 1) {
                this.activeImage = 0
            }
        },

        prev() {
            this.activeImage--
            if (this.activeImage < 0) {
                this.activeImage = this.slides.length - 1
            }
        },

        autoplay() {
            this.auto = setInterval(this.next, 3000);
        },
    },

    created() {
        this.autoplay()

    }

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


                <img :src="slides[activeImage].image" alt="">
                <p><i>“{{ slides[activeImage].quote }}”</i></p>
                <h6 style="font-weight: 700;">{{ slides[activeImage].name }}</h6>
                <div class="controls d-flex gap-3">
                    <svg v-if="activeImage === 0" xmlns="http://www.w3.org/2000/svg" @click="prev()" height="1em"
                        viewBox="0 0 512 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                        <path d="M256 512A256 256 0 1 0 256 0a256 256 0 1 0 0 512z" />
                    </svg>
                    <svg v-else xmlns="http://www.w3.org/2000/svg" @click="next()" height="1em"
                        viewBox="0 0 512 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                        <path
                            d="M464 256A208 208 0 1 0 48 256a208 208 0 1 0 416 0zM0 256a256 256 0 1 1 512 0A256 256 0 1 1 0 256z" />
                    </svg>


                    <svg v-if="activeImage === 0" xmlns="http://www.w3.org/2000/svg" @click="next()" height="1em"
                        viewBox="0 0 512 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                        <path
                            d="M464 256A208 208 0 1 0 48 256a208 208 0 1 0 416 0zM0 256a256 256 0 1 1 512 0A256 256 0 1 1 0 256z" />
                    </svg>
                    <svg v-else xmlns="http://www.w3.org/2000/svg" @click="prev()" height="1em"
                        viewBox="0 0 512 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                        <path d="M256 512A256 256 0 1 0 256 0a256 256 0 1 0 0 512z" />
                    </svg>
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

svg {
    cursor: pointer;
}

p {
    font-size: 1.3rem;
}
</style>