<template>
    <nav class="navbar fixed-top navbar-expand-lg">
        <div class="container py-2">
            <div class="navbar-brand">
                <img src="/imgs/LogoSM.png" class="img-fluid">
            </div>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <i class="fa-solid fa-bars"></i>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav">
                    <a class="nav-link active" aria-current="page" href="#">Home</a>
                    <a class="nav-link" href="#about">about</a>
                    <a class="nav-link" href="#servizi">servizi</a>
                    <a class="nav-link" href="#progetti">progetti</a>
                    <a class="nav-link" href="#contatti">contatti</a>
                </div>
            </div>
        </div>
    </nav>
</template>

<script>
export default {
    
}
</script>

<style scoped lang="scss">
@use "../styles/partials/variables" as *;
.container {
    border-bottom: 1px solid $color-gold;

    .navbar-brand{
        width: 6rem;
    }

    .navbar-toggler{
        border: none;
        background-color: transparent;

        &:focus{
            box-shadow: none;
        }
    }

    .navbar-collapse{
        justify-content: end;

        .nav-link {
            text-transform: uppercase;
            padding: .5rem;
        }
    }
}
</style>