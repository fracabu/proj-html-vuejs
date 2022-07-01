<template>
    <div class="container-jumbo"> 
    <div class="nav py-3">
        <div class="d-flex flex-grow-1">
            <img :src="require('../assets/img/avada-charity-logo.png')" alt="" class="logo-nav d-flex">
        </div>
        <ul class="menu-nav d-flex text-white text-uppercase px-3">
            <li v-for="(menu, i) in ListaMenu" :key="i">
                {{ menu.text }}
            </li>
        </ul>
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
            ]
        }
    }


}

</script>

<style lang="scss" scoped>

.container-jumbo{
    background-image: url('../assets/img/home-page-slider.jpg');
    background-repeat: no-repeat;
    background-size: cover;
   
    height: 500px;
}

.logo-nav {
    width: 200px;
    margin-left: 50px;
}

;




</style>