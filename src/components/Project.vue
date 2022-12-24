<template>
  <section id="progetti" class="pt-5">
    <div class="container">
      <h2 class="title-section"><span>Progetti</span></h2>

      <div class="project-grid">
        <figure class="image-1">
          <img src="/imgs/pav1.JPG"
              class="figure" alt="">
          <div class="overlay">
            <div class="overlay-text">Lucidatura palladiana di marmo</div>
          </div>
        </figure>
        <figure class="image-2">
          <img src="/imgs/pav-cubo.JPG"
              class="figure" alt="">
          <div class="overlay">
            <div class="overlay-text">Levigatura semilucida pavimento 3D in marmo</div>
          </div>
        </figure>
        <figure class="image-3">
          <img src="/imgs/pav-stella.JPG" class="figure"
              alt="">
          <div class="overlay">
            <div class="overlay-text">Lucidatura pavimento in marmo bianco</div>
          </div>
        </figure>
        <figure class="image-4">
          <img src="/imgs/piano-cucina.JPG"
              class="figure" alt="">
          <div class="overlay">
            <div class="overlay-text">Lucidatura piano cucina in marmo</div>
          </div>
        </figure>
        <figure class="image-5">
          <img src="/imgs/pav-3.JPG"
              class="figure" alt="">
          <div class="overlay">
            <div class="overlay-text">Lucidatura pavimento in palladiana di marmo</div>
          </div>
        </figure>
        <figure class="image-6">
          <img src="/imgs/pav-2.JPG" class="figure" alt="">
          <div class="overlay">
            <div class="overlay-text">Lucidatura pavimento in marmo</div>
          </div>
        </figure>
        <div class="text">
          <p>Per vedere la differenza tra il pavimento prima dell'intervento e il dopo. Clicca qui!</p>
          <button class="btn project-btn" @click="onProjectClick">Clicca per vedere i progetti</button>
        </div>
      </div>
    </div>

    <AllProject></AllProject>
  </section>
</template>

<script>
import { store } from "../store";
import AllProject from "./AllProject.vue";

export default {
  components: { AllProject },
  data() {
    return {
      store,
    }
  },
  computed: {
    onProjectClick(){
      store.projectBtn = true;
      store.closeProject = false
    }
  }
}
</script>

<style scoped lang="scss">
@use "../styles/partials/variables" as *;
@use "../styles/partials/utilities" as *;

.project-grid {
  display: grid;
  grid-template-columns: repeat(8, 1fr);
  grid-template-rows: repeat(7, 5vw);
  grid-gap: 1rem;

  .figure {
    width: 100%;
    height: 100%;
    object-fit: cover;
    display: block;
  }

  .image-1 {
    grid-column: 1 / 3;
    grid-row: 1 / 3;

    .figure {
      object-position: 10% 40%;
    }
  }

  .image-2 {
    grid-column: 3 / 5;
    grid-row: 1 / 3;

    .figure {
      object-position: 10% 70%;
    }
  }

  .image-3 {
    grid-column: 5 / 9;
    grid-row: 1 / 6;
  }

  .image-4 {
    grid-column: 1 / 5;
    grid-row: 3 / 6;

    .figure {
      object-position: 10% 25%;
    }
  }

  .image-5 {
    grid-column: 1 / 3;
    grid-row: 6 / 8;

    .figure {
      object-position: 10% 55%;
    }
  }

  .image-6 {
    grid-column: 3 / 5;
    grid-row: 6 / 8;
  }

  .text {
    grid-column: 5 / 9;
    grid-row: 6 / 8;
    text-align: center;
    padding: 1rem 0;
  }

  figure {
    position: relative;
  }

  .overlay {
    position: absolute;
    top: 0;
    bottom: 0;
    right: 0;
    left: 0;
    height: 100%;
    width: 100%;
    opacity: 0;
    transition: .5s ease;
    background-color: white;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .overlay:hover {
    opacity: 0.7;
  }

  .overlay-text {
    color: black;
    text-align: center;
  }
}

.project-btn {
  color: $color-gold;
  border-color: $color-gold;

  &:hover,
  &:active{
    color: #fff;
    background-color: $color-gold;
  }
}
</style>