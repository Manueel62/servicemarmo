<template>
    <div class="container py-4" :class="(store.projectBtn === true && store.closeProject === false) ? 'd-block' : 'd-none'">
        <div class="row">
            <div class="col-6">
                <div class="card mb-3" style="max-width: 700px;">
                    <div class="row g-0">
                        <div class="col-md-4">
                            <img src="/imgs/marmo-carrara.JPG" class="img-fluid rounded-start" alt="...">
                        </div>
                        <div class="col-md-8">
                            <div class="card-body">
                                <h5 class="card-title">Lucidatura pavimento in marmo di Carrara</h5>
                                <p class="card-text">This is a wider card with supporting text below as a natural
                                    lead-in to additional content. This content is a little bit longer.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-6">
                <div class="card mb-3" style="max-width: 700px;">
                    <div class="row g-0">
                        <div class="col-md-4">
                            <img src="/imgs/macchia.JPG" class="img-fluid rounded-start" alt="...">
                        </div>
                        <div class="col-md-8">
                            <div class="card-body">
                                <h5 class="card-title">Rimozione macchia dovuta a un prodotto aggressivo</h5>
                                <p class="card-text">This is a wider card with supporting text below as a natural
                                    lead-in to additional content. This content is a little bit longer.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-6">
                <div class="card mb-3" style="max-width: 700px;">
                    <div class="row g-0">
                        <div class="col-md-4">
                            <img src="/imgs/seminato-granito.JPG" class="img-fluid rounded-start" alt="...">
                        </div>
                        <div class="col-md-8">
                            <div class="card-body">
                                <h5 class="card-title">Levigatura pavimento in seminato di granito</h5>
                                <p class="card-text">This is a wider card with supporting text below as a natural
                                    lead-in to additional content. This content is a little bit longer.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-6">
                <div class="card mb-3" style="max-width: 700px;">
                    <div class="row g-0">
                        <div class="col-md-4">
                            <img src="/imgs/semilucidatura.JPG" class="img-fluid rounded-start" alt="...">
                        </div>
                        <div class="col-md-8">
                            <div class="card-body">
                                <h5 class="card-title">Semilucidatura di un piano di cucina in marmo</h5>
                                <p class="card-text">This is a wider card with supporting text below as a natural
                                    lead-in to additional content. This content is a little bit longer.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

        </div>

        <div class="text-center">
            <button class="btn btn-dark" @click="closeProject">
                <i class="fa-solid fa-arrow-up-from-bracket"></i>
                chiudi
            </button>
        </div>
    </div>
</template>

<script>
import { store } from "../store";

export default {
    data() {
        return {
            store
        }
    },
    computed: {
        closeProject(){
            store.closeProject = true;
            store.projectBtn = false
        }
    }
}

</script>

<style scoped lang="scss">

</style>