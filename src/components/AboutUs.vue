<template>
    <section id="about" class="pt-5">
        <div class="container">
            <h2 class="title-section">about <span>Service Marmo</span></h2>

            <div class="row gx-5">
                <div class="col-12 col-md-4">
                    <h4 class="pb-md-4">professionalitá, esperienza, qualitá</h4>
                    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Doloremque veniam temporibus, debitis
                        nesciunt illo perferendis, exercitationem laudantium corporis, porro quas corrupti obcaecati a!
                        Harum facilis sunt neque officiis fugit odit.
                    </p>
                </div>

                <div class="col-12 col-md-4 mb-3">
                    <h4 class="pb-md-4">aree di specializzazione:</h4>
                    <div class="row gy-3">
                        <div class="col-6 col-md-12">
                            <div class="icon">
                                <img src="/imgs/icon/floor-cleaner.png" alt="" class="img-fluid">
                            </div>
                            <div class="py-2 text">LEVIGATURA</div>
                        </div>
                        <div class="col-6 col-md-12">
                            <div class="icon">
                                <img src="/imgs/icon/clean-floor.png" alt="" class="img-fluid">
                            </div>
                            <div class="py-2 text">LUCIDATURA</div>
                        </div>
                    </div>
                </div>

                <div class="col-12 col-md-4">
                    <h4 class="pb-md-4">non solo marmo:</h4>
                    <div class="row">
                        <div class="col-4 col-md-12 d-flex align-items-center gap-3">
                            <div class="square">
                                <img src="/imgs/granito.jpg" alt="" class="img-block">
                            </div>
                            <div class="py-3">GRANITO</div>
                        </div>
                        <div class="col-4 col-md-12 d-flex align-items-center gap-3">
                            <div class="square">
                                <img src="/imgs/cotto.jpg" alt="" class="img-block">
                            </div>
                            <div class="py-3">COTTO</div>
                        </div>
                        <div class="col-4 col-md-12 d-flex align-items-center gap-3">
                            <div class="square">
                                <img src="/imgs/granito.jpg" alt="" class="img-block">
                            </div>
                            <div class="py-3">ALTRO</div>
                        </div>
                    </div>
                </div>

                <!-- <div class="col-12 col-md-4">
                    <div class="number">30</div>
                    <div class="text">Anni di esperienza</div>
                </div> -->
            </div>
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
@use "../styles/partials/utilities" as *;
@use "../styles/partials/variables" as *;

h4 {
    font-size: 1.3rem;
    // padding-bottom: 1rem;
}
.icon {
    width: 2rem;
}

.square{
    width: 2rem;
    // height: 2rem;
    aspect-ratio: 1/1;

    .img-block{
        display: block;
        width: 100%;
        height: 100%;
        object-fit: cover;
    }
}
// .number {
// 	font-size: 8rem;
// 	font-weight: 700;
// 	background-clip: text;
// 	-webkit-background-clip: text;
// 	color: transparent;
// 	background-image: url('/imgs/sfondo.jpg');
// }

.text{
    text-transform: uppercase;
    font-weight: 600;
    letter-spacing: 1px;
}   
</style>