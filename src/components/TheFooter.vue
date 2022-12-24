<template>
    <footer id="contatti">
        <div class="container">
            <h2 class="title-section"><span>Contattaci</span></h2>

            <div class="row justify-content-center">
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
            </div>

            <div class="py-5 text-center">
                <nav aria-label="breadcrumb">
                    <ol class="breadcrumb justify-content-center">
                        <li class="breadcrumb-item"><a href="#home">Home</a></li>
                        <li class="breadcrumb-item"><a href="#about">About</a></li>
                        <li class="breadcrumb-item"><a href="#servizi">Servizi</a></li>
                        <li class="breadcrumb-item"><a href="#progetti">Progetti</a></li>
                    </ol>
                </nav>
            </div>

        </div>

        <div class="attribute text-center">
            <a href="https://www.flaticon.com/free-icons/floor" target="_blank"
                title="floor icons">Floor icons created by Freepik - Flaticon / </a>

            <a href="https://www.flaticon.com/free-icons/texture" target="_blank"
                title="texture icons">Texture icons created by Smashicons - Flaticon / </a>

            <a href="https://www.flaticon.com/free-icons/cleaning" target="_blank"
                title="cleaning icons">Cleaning icons created by Freepik - Flaticon / </a><br>

            <a href="https://www.flaticon.com/free-icons/floor-mop" target="_blank"
                title="floor mop icons">Floor mop icons created by Freepik - Flaticon / </a>

            <a href="https://www.flaticon.com/free-icons/stairs" target="_blank"
                title="stairs icons">Stairs icons created by Freepik - Flaticon / </a>

            <a href="https://www.flaticon.com/free-icons/bathroom" target="_blank"
                title="bathroom icons">Bathroom icons created by piksart - Flaticon / </a>
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

footer {
    padding-bottom: 1rem;
    background-color: #393730;
    color: #fff;

    .information {
        font-weight: 600;
    }

    .right-part {
        text-align: end;
    }

    .breadcrumb-item a{
        color: $color-gold;
        text-transform: uppercase;
    }

    .attribute {
        font-size: .8rem;
        padding: 0 0 1rem 1rem;

        a {
            text-decoration: none;
            color: $color-grey;
        }
    }
}
</style>