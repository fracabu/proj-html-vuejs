<template>
    <div class="container">
        <div class="jumbo">
            <div class="nav py-3">
                <div class="d-flex flex-grow-1">
                    <img :src="require('../assets/img/avada-charity-logo.png')" alt="" class="logo-nav d-flex">
                </div>
                <ul class="menu-nav d-flex text-white text-uppercase px-3 list-unstyled">
                    <li class="menu" v-for="(menu, i) in ListaMenu" :key="i">
                        {{ menu.text }}
                    </li>
                </ul>
            </div>
            <div class="container-title">
                <span class="text-center text-uppercase text-white fs-1 fw-light"> make a difference</span>
            </div>
            <div class="container">
                <p class="text-white opacity-75 py-2">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Illum
                    culpa temporibus reiciendis </p>
            </div>
            <div class="container-button">
                <button class="btn btn-outline-secondary mx-2">our mission</button>
                <button class="btn btn-outline-warning">donate now</button>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            ListaMenu: [
                { text: 'home' },
                { text: 'mission' },
                { text: 'cause' },
                { text: 'journal' },
                { text: 'donate' },
            ]
        }
    }


}

</script>

<style lang="scss" scoped>
.jumbo {
    background-image: url('../assets/img/home-page-slider.jpg');
    background-repeat: no-repeat;
    background-size: cover;

    height: 500px;
}

;

.logo-nav {
    width: 200px;
    margin-left: 50px;
}

;

.container-title {
    margin-top: 100px;

}

;

.menu {
    
    margin-right: 60px;
    font-size: 10px;
    
}

.menu:hover{
    background: #fcd66c;
}
</style>