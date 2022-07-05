<template>
    <div>
        <div class="container-footer">
            <div class="container-logo py-3">
                <img :src="require('../assets/img/avada-charity-mobile-logo.png')" alt="">
            </div>
            <div class="container-copy">
                <span class="copyright"> Lorem ipsum, dolor sit amet consectetur adipisicing elit. Temporibus porro quia
                    debitis hic placeat sunt, fuga quasi eos dignissimos incidunt provident amet voluptatem suscipit
                    perspiciatis error? Molestias iure sunt dolores?</span>

                <div class="container-icon d-flex justify-content-center">
                    <ul>
                        <li> <img :src="iconaUrl" alt=""> </li>
                    </ul>
                    <ul>
                        <li><img :src="iconaUrl" alt=""></li>
                    </ul>
                    <ul>
                        <li><img :src="iconaUrl" alt=""></li>
                    </ul>
                    <ul>
                        <li><img :src="iconaUrl" alt=""></li>
                    </ul>
                </div>
            </div>
        </div>

    </div>
</template>

<script>
export default {

    props:{
        iconaUrl: String,
    },
    data() {
        return {
        
        }
    }

}

</script>

<style lang="scss" scoped>
.container-copy {
    background-color: lightgray;
    height: 100px;
}

.copyright {
    font-size: 8px;
}
</style>