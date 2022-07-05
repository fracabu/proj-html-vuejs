<template>
    <div>
        <!-- SEZIONE EVERY MOMENT COUNTS -->
        <div class="container">
            <div class="row d-flex g-0">
                <div class="col-8">
                    <h1 class="text-uppercase fs-3 text-start mt-5 px-5">every moment count</h1>
                    <div class="text-start px-5">
                        <hr>
                    </div>
                    <div>
                        <p class="text-start fs-6 py-3 px-5">Lorem ipsum dolor sit amet consectetur adipisicing elit.
                            Tenetur,quibusdam consectetur quam</p>
                    </div>
                    <div>
                        <p class="text-start fs-6 py-3 px-5">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Vel quidem
                            id harum eos quos quam </p>
                    </div>
                    <div>
                        <p class="text-start fs-6 py-3 px-5">Lorem ipsum dolor sit amet consectetur adipisicing elit.
                            Tenetur,quibusdam consectetur quam</p>
                    </div>
                    <div class="d-flex align-items-start py-5 px-5">
                        <div class="btn btn-outline-warning align-start">our mission</div>
                    </div>
                </div>
                <div class="col-4">
                    <div class="container py-3 mt-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Incidunt aut natus odio quisquam, iure
                        expedita nobis aspernatur facere, harum dicta adipisci repudiandae. Ex debitis ipsa quos, ullam
                        nam neque illo!</div>
                    <div class="container py-3" >Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor, provident sequi commodi et non
                        in tempore facere est, consectetur quis quos modi iure vitae vel qui omnis explicabo nulla
                        facilis!</div>
                    <div class="container py-3" >Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor expedita possimus sequi est
                        quibusdam quia! Qui unde incidunt, perferendis, praesentium enim placeat tempore facere
                        molestias illo eum nam aliquam natus?</div>
                </div>
            </div>
        </div>



        <!-- SEZIONE OUR VALUES -->
        <div class="container">
            <div class="bg-img">
                <div class="container py-5">
                    <h1 class="text-white text-center text-uppercase fs-3 mt-5">our values</h1>
                </div>
                <div class="row py-5 text-white">
                    <div class="col-3">
                        <div>icona</div>
                        <div>testo icona</div>
                        <div>testo</div>
                        <div><button>clicca</button></div>
                    </div>
                    <div class="col-3">
                        <div>icona</div>
                        <div>testo icona</div>
                        <div>testo</div>
                        <div><button>clicca</button></div>
                    </div>
                    <div class="col-3">
                        <div>icona</div>
                        <div>testo icona</div>
                        <div>testo</div>
                        <div><button>clicca</button></div>
                    </div>
                    <div class="col-3">
                        <div>icona</div>
                        <div>testo icona</div>
                        <div>testo</div>
                        <div><button>clicca</button></div>
                    </div>
                </div>
            </div>
        </div>

        <!-- SEZIONE RECENT CAUSES -->
        <div class="container py-5">
            <div class="text center text-uppercase">
                <h1> recent causes</h1>
                <span>_____________</span>
            </div>
            <div class="py-5">
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quasi dolores eius mollitia</p>
            </div>
            <div class="row">
                <div class="col-3">
                    <img src="../assets/img/avada-charity-fair-trade-featured-200x150.jpg" alt="">
                </div>
                <div class="col-3">
                    <img src="../assets/img/avada-charity-shelter-featured-200x150.jpg" alt="">
                </div>
                <div class="col-3">
                    <img src="../assets/img/avada-charity-farming-featured-200x150.jpg" alt="">
                </div>
                <div class="col-3">
                    <img src="../assets/img/avada-charity-vaccines-featured-200x150.jpg" alt="">
                </div>
            </div>
        </div>
                <!-- SEZIONE VIEW ALL OUR CAUSES -->
        <div class="container-our-causes py-5 mt-5">
            <span class="text-center text-white text-uppercase "> view all our causes </span>
        </div>

        <div class="container-icon d-flex justify-content-center">
                    <ul>
                        <li> <TheFooter :icona-url = "iconaUrl" ></TheFooter> </li>
                    </ul>

    </div>
    </div>
</template>

<script>
import TheFooter from "./TheFooter.vue";

export default {
    components:{TheFooter},
    data(){
        return{
            iconaUrl:"../assets/img/instagram-brands"
        }
    }

}

</script>

<style lang="scss" scoped>
;

.col-4 {
    background-color: #ED6866;

}

;

.bg-img {
    background-image: url('../assets/img/home-content-bg-2.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    height: 500px;

}

.container-our-causes{
    background-color: #ED6866

}

;
</style>
