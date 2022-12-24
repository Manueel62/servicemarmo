<template>
    <header class="d-flex" id="home">
        <NavBar></NavBar>

        <div class="jumbotron flex-grow-1">
            <div class="container">
                <h1>Service <br> Marmo</h1>

                <div class="line my-3"></div>

                <div>di Citrini Nicola</div>
            </div>
        </div>
    </header>
</template>

<script>
import NavBar from './NavBar.vue';

export default {
    components: { NavBar }
}
</script>

<style scoped lang="scss">
@use "../styles/partials/variables" as *;

header{
    background-image: url('/imgs/sfondo.jpg');
    background-size: cover;
    background-position: center;
    height: 100vh;

    .jumbotron{
        padding-top: 8rem;
        font-family: 'Lora', serif;
        display: flex;
        align-items: center;

        h1 {
            letter-spacing: .5rem;
            font-weight: bolder;
            text-transform: uppercase;
        }

        .line{
            width: 2rem;
            border: 2px solid $color-gold ;
        }
    }

   
}
</style>