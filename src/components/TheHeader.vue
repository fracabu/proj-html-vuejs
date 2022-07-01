<template>

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
.nav {
    position: relative;
    z-index: 1;
    flex-grow: 1;
}

.logo-nav {
    width: 200px;
    margin-left: 50px;
}

;




</style>