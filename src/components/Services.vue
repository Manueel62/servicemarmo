<template>
    <section id="servizi" class="pt-5">
        <div class="container">
            <h2 class="title-section pb-0"><span>Servizi</span></h2>
            <p class="text-center">Levigatura e lucidatura marmo, granito, cotto</p>

            <div class="row g-5">
                <div class="col-6 col-md-4">
                    <div class="my-card">
                        <div class="icon">
                            <img src="/imgs/icon/pavimenti.png" alt="" class="img-fluid">
                        </div>
                        <h4>Pavimenti</h4>
                        <p>Lucidatura e levigatura al fine di rimuovere macchie, graffi e ulteriori         danneggiamenti. Anche le fughe vengono pulite e riparate.
                        </p>
                    </div>
                </div>
                <div class="col-6 col-md-4">
                    <div class="my-card">
                        <div class="icon">
                            <img src="/imgs/icon/Rivestimenti.png" alt="" class="img-fluid">
                        </div>
                        <h4>Rivestimenti</h4>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ducimus, repudiandae consequuntur
                            itaque quis culpa.
                        </p>
                    </div>
                </div>
                <div class="col-6 col-md-4">
                    <div class="my-card">
                        <div class="icon">
                            <img src="/imgs/icon/top-bagno-cucina.png" alt="" class="img-fluid">
                        </div>
                        <h4>Top bagni e cucine</h4>
                        <p>Non solo pavimenti: lucidatura e levigatura di piani cucina, lavandini, piani doccia. L'obiettivo é il recupero dell'originale.
                        </p>
                    </div>
                </div>
                <div class="col-6 col-md-4">
                    <div class="my-card">
                        <div class="icon">
                            <img src="/imgs/icon/scale.png" alt="" class="img-fluid">
                        </div>
                        <h4>Rilucidatura scale</h4>
                        <p>Lucidatura e levigatura di gradini, con stuccature delle fuga e riparazione di eventuali danni. <br> Risultato: brillantezza.
                        </p>
                    </div>
                </div>
                <div class="col-6 col-md-4">
                    <div class="my-card">
                        <div class="icon">
                            <img src="/imgs/icon/pav-anticati.png" alt="" class="img-fluid">
                        </div>
                        <h4>Pavimenti anticati</h4>
                        <p>Pulizia e lucidatura/levigatura di pavimenti anticati al fine di ripristinarne le condizioni ottimali. L'obiettivo é di portare il pavimento allo splendore precedente.
                        </p>
                    </div>
                </div>
                <div class="col-6 col-md-4">
                    <div class="my-card">
                        <div class="icon">
                            <img src="/imgs/icon/pulizia.png" alt="" class="img-fluid">
                        </div>
                        <h4>Trattamenti e pulizie straordinarie</h4>
                        <p>Trattamenti idrorepellenti e oleorepellenti protettivi per garantire una migliore conservazione del pavimento, prevenendo l'insorgenza di macchie.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
</script>

<style scoped lang="scss">
@use "../styles/partials/variables" as *;
@use "../styles/partials/utilities" as *;

.my-card {
    background-color: $color-white;
    padding: 2rem;

    .icon {
        width: 2rem;
        margin-bottom: 1rem;
    }
}

h4 {
    font-weight: 600;
    font-size: larger;
    // letter-spacing: 1px;
}
</style>