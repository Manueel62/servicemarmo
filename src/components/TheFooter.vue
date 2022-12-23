<template>
    <footer id="contatti">
        <div class="container">
            <h2 class="title-section"><span>Contattaci</span></h2>

            <div class="row justify-content-center">
                <!-- <div class="col-3"></div> -->
                <div class="col-6 col-lg-4 col-xl-3">
                    <div>
                        <i class="fa-brands fa-whatsapp pe-2"></i>
                        Cellulare: 
                        <span class="information"> 338 658 1610</span>
                    </div>
                    <div>
                        <i class="fa-solid fa-phone pe-2"></i>
                        Natel:
                        <span class="information"> 079 762 4016</span>
                    </div>
                    <div>
                        <i class="fa-regular fa-envelope pe-2"></i>
                        E-mail:
                        <span class="information"> nicola.citrini@alice.it</span>
                    </div>
                    <div>
                        <i class="fa-solid fa-at pe-2"></i>
                        Pec:
                        <span class="information"> nicolacitrini@postecert.it</span>
                    </div>
                </div>
                <div class="col-6 col-lg-4 col-xl-3 right-part">
                    <div>Via Tre Leghe, 10 <br> IT - 23022 Chiavenna (SO)</div>
                    <div>Partita IVA: 01046250146</div>
                    <div>Codice Fiscale: CTRNCL66H16Z133U</div>
                </div>
                <!-- <div class="col-3"></div> -->
            </div>

            <!-- <div>icon design by <a href="//www.flaticon.com/free-icons/floor" >Floor icons created by Smashicons - Flaticon</a></div> -->
            
        </div>
    </footer>
</template>

<script>
export default {
    
}
</script>

<style scoped lang="scss">
@use "../styles/partials/variables" as *;
@use "../styles/partials/utilities" as *;

footer{
    padding-bottom: 3rem;
    background-color: #393730;
    color: #fff;

    .information{
        font-weight: 600;
    }

    .right-part{
        text-align: end;
    }
}

</style>