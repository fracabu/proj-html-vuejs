<template>
    <div>
        <div class="container-jumbo">
            <img :src="require('../assets/img/home-page-slider.jpg')" alt="" class="jumbo-img">
        </div>
        <div class="container">
            <div class="row d-flex ">
                <div class="col-8">
                    <h1 class="text-uppecase text start">every moment count</h1>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur, quibusdam consectetur quam porro iure magni alias fuga numquam, tempora voluptate id explicabo accusantium ullam aut distinctio modi ipsam praesentium sunt?</p>
                    <div><button>our mission</button></div>
                </div>
                <div class="col-4">
                    <div>Lorem ipsum dolor sit amet consectetur adipisicing elit. Incidunt aut natus odio quisquam, iure
                        expedita nobis aspernatur facere, harum dicta adipisci repudiandae. Ex debitis ipsa quos, ullam
                        nam neque illo!</div>
                    <div>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor, provident sequi commodi et non
                        in tempore facere est, consectetur quis quos modi iure vitae vel qui omnis explicabo nulla
                        facilis!</div>
                    <div>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor expedita possimus sequi est
                        quibusdam quia! Qui unde incidunt, perferendis, praesentium enim placeat tempore facere
                        molestias illo eum nam aliquam natus?</div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}

</script>

<style lang="scss" scoped>
.container-jumbo {
    position: absolute;
    top: 0;
    right: 0;
    left: 0;
    right: 0;
}

;

.jumbo-img {
    width: 100%;
    height: 300px;

}

.row {
    position: relative;
    margin-top: 238px;
    border: 1px solid black;
}

.col-4 {
    background-color: #ED6866;
}
</style>