<script>
export default {
    name: 'SiteHeader',
    data() {
        return {
            items: [
                {
                    name: 'Home'
                },
                {
                    name: 'About'
                },
                {
                    name: 'Services'
                },
                {
                    name: 'Work'
                },
                {
                    name: 'Articles'
                },
            ]
        }
    },
}
</script>
<template>
    <header>
        <nav class="navbar navbar-expand-lg ">
            <div class="container-fluid header-wrapper">
                <a class="navbar-brand" href="#">
                    <img src="../assets/img/construction_logo.png" alt="Avada Construction">
                </a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarTogglerDemo02"
                    aria-controls="navbarTogglerDemo02" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse justify-content-end" id="navbarTogglerDemo02">
                    <ul class="navbar-nav mb-2 mb-lg-0 gap-4">
                        <li v-for="item in items" class="nav-item">
                            <a class="nav-link " aria-current="page" href="#">{{ item.name }}</a>
                        </li>

                        <div class="yellow-btn">
                            <button>GET QUOTE</button>
                        </div>
                    </ul>

                </div>
            </div>
        </nav>
    </header>
</template>


<style lang="scss" scoped>
@use "../assets/scss/partials/variables.scss" as *;

.header-wrapper {
    width: 90%;
}

.navbar-brand img {
    width: 8rem;
}

.nav-item {
    text-transform: uppercase;
}

.nav-item .active {
    color: $avd-primary;
}

.yellow-btn {
    display: flex;

}

.yellow-btn button {
    border: none;
    text-align: center;
    background-color: $avd-primary;
    color: #000000A6;
    padding: 0 1rem;
}

button:hover {
    background-color: $avd-lightDark;
    color: $avd-white;
}
</style>