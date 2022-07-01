<template>
    <div>
        <div class="container-jumbo">
            <img :src="require('../assets/img/home-page-slider.jpg')" alt="" class="jumbo-img">
        </div>
        <div class="container">
            <div class="row d-flex ">
            <div class="col-8">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Libero, soluta. Consectetur ex incidunt assumenda nam quasi, mollitia voluptates fugiat aliquam recusandae expedita! Ad aliquid corrupti necessitatibus, explicabo facilis quas deleniti!</div>
            <div class="col-4"> Lorem ipsum dolor sit amet, consectetur adipisicing elit. Excepturi pariatur distinctio perferendis rem asperiores sunt qui labore? Doloribus praesentium odit adipisci veritatis dicta molestiae dolore dolores ipsum quasi, qui accusamus!</div>   
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
};

.jumbo-img {
    width: 100%;
    height: 300px;

}

.row{
    position: relative;
    margin-top: 238px;
    border: 1px solid black;
}

.col-4{
    background-color: #ED6866;
}


</style>