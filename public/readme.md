                            <!-- THE HEADER -->

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