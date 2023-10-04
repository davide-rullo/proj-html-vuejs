        
<script>
export default {
    name: 'AppNews'
}
</script>
<template>
    <section class="news">
        <div class="container pt-5">
            <div class="news-row">
                <p>Latest News</p>
                <div class="hrow">
                </div>
                <div class="news-subtitle text-center pt-4 pb-5">
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe architecto consectetur quis corrupti
                        quas.
                        Illo, magnam?</p>
                </div>
            </div>
            <div class="row row-cols-1 row-cols-sm-2 row-cols-md-3">
                <div class="col mb-2">
                    <div class="card h-100">
                        <img src="../assets/img/blog-post-134132600-1200x723.jpg" class="card-img-top" alt="...">
                        <div class="card-body">

                            <a href="#">
                                <p class="card-text">Redeveloping Florida’s Remote Southern Coast</p>
                            </a>
                            <h6>December 7th, 2015</h6>
                            <div class="card-hr"></div>
                            <p class="article-text">Technology is Here to Stay Lorem ipsum dolor sit amet, consectetur
                                adipiscing elit. Vivamus
                                purus nisl, elementum vitae consequat at, tristique ut enim. Sed ut dignissim leo. Nullam
                                sed metus id sapien faucibus rhoncus sed</p>

                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card h-100">
                        <img src="../assets/img/blog-post-332773904-1200x723.jpg" class="card-img-top" alt="...">
                        <div class="card-body">

                            <a href="#">
                                <p class="card-text">How We Manage Large Construction Projects</p>
                            </a>
                            <h6>December 7th, 2015</h6>
                            <div class="card-hr"></div>
                            <p class="article-text">Technology is Here to Stay Lorem ipsum dolor sit amet, consectetur
                                adipiscing elit. Vivamus
                                purus nisl, elementum vitae consequat at, tristique ut enim. Sed ut dignissim leo. Nullam
                                sed metus id sapien faucibus rhoncus sed</p>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card h-100">
                        <img src="../assets/img/blog-post-92486644-1200x723.jpg" class="card-img-top" alt="...">
                        <div class="card-body">

                            <a href="#">
                                <p class="card-text">Future proofing a modern home</p>
                            </a>
                            <h6>December 6th, 2015</h6>
                            <div class="card-hr"></div>
                            <p class="article-text">Technology is Here to Stay Lorem ipsum dolor sit amet, consectetur
                                adipiscing elit. Vivamus
                                purus nisl, elementum vitae consequat at, tristique ut enim. Sed ut dignissim leo. Nullam
                                sed metus id sapien faucibus rhoncus sed</p>

                        </div>
                    </div>
                </div>
            </div>
            <div class="others d-flex justify-content-center align-items-center pb-5">
                <div class="others-hr">

                </div>
                <p>VIEW ALL ARTICLES</p>
                <div class="others-hr">

                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
a {
    text-decoration: none;
    color: black;
}

h6 {
    font-size: .7rem;
    color: grey;
    margin-top: 0.5rem;
}

.news {
    background-color: #f5f5f5;

}

.news-row p {
    font-size: 1.5rem;
    text-align: center;
}

.news-subtitle p {
    font-size: .9rem;
}

.card-text {
    font-size: 1.3rem;
}

.card-hr {
    width: 98%;
    margin: auto;
    height: 1px;
    background-color: #80808040;
}

.article-text {
    color: grey;
    font-weight: 400;
    margin-top: 0.5rem;
}
</style>