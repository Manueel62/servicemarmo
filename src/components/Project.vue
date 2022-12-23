<template>
    <section id="progetti" class="pt-5">
        <div class="container">
            <h2 class="title-section"><span>Progetti</span></h2>

            <div class="project-grid">
                <figure class="image-1">
                    <img src="https://www.gres-sassuolo.it/wp-content/uploads/Pure-Marble-Effetto-Marmo-sodalite-blu1-650x650.jpg"
                        class="figure" alt="">
                    <div class="overlay">
                        <div class="overlay-text">Pavimento</div>
                    </div>
                </figure>
                <figure class="image-2">
                    <img src="https://sp-ao.shortpixel.ai/client/q_glossy,ret_img,w_1000/https://www.besidebathrooms.com/wp-content/uploads/Piastrelle-effetto-marmo-abk-sensi-signoria-LABRADORITE-LUX-LILAC-GREY.jpg"
                        class="figure" alt="">
                    <div class="overlay">
                        <div class="overlay-text">Bagno</div>
                    </div>
                </figure>
                <figure class="image-3">
                    <img src="https://www.marmibianco.com/wp-content/uploads/2019/08/scale-in-marmo.jpg" class="figure"
                        alt="">
                    <div class="overlay">
                        <div class="overlay-text">Rilucidatura scale</div>
                    </div>
                </figure>
                <figure class="image-4">
                    <img src="https://www.renziceramiche.it/wp-content/uploads/2020/07/i-pavimenti-in-marmo.jpg"
                        class="figure" alt="">
                    <div class="overlay">
                        <div class="overlay-text">Trattamenti e pulizie</div>
                    </div>
                </figure>
                <figure class="image-5">
                    <img src="https://www.facileristrutturare.it/wp-content/uploads/2021/12/cucina-minimal-2-800x532.png"
                        class="figure" alt="">
                    <div class="overlay">
                        <div class="overlay-text">Cucina</div>
                    </div>
                </figure>
                <figure class="image-6">
                    <img src="https://storage.clerici.eu/3/html-template/61e5837610b64.png" class="figure" alt="">
                    <div class="overlay">
                        <div class="overlay-text">Top bagno</div>
                    </div>
                </figure>
            </div>

        </div>

    </section>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
@use "../styles/partials/variables" as *;
@use "../styles/partials/utilities" as *;

.project-grid {
  display: grid;
  grid-template-columns: repeat(8, 1fr);
  grid-template-rows: repeat(7,5vw);
  grid-gap: 20px;
}

.figure {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}

.image-1 {
  grid-column-start: 1;
  grid-column-end: 3;
  grid-row-start: 1;
  grid-row-end: 3;
}

.image-2 {
  grid-column-start: 3;
  grid-column-end: 5;
  grid-row-start: 1;
  grid-row-end: 3;
}

.image-3 {
  grid-column-start: 5;
  grid-column-end: 9;
  grid-row-start: 1;
  grid-row-end: 8;
}

.image-4 {
  grid-column-start: 1;
  grid-column-end: 5;
  grid-row-start: 3;
  grid-row-end: 6;
}

.image-5 {
  grid-column-start: 1;
  grid-column-end: 3;
  grid-row-start: 6;
  grid-row-end: 8;
}

.image-6 {
  grid-column-start: 3;
  grid-column-end: 5;
  grid-row-start: 6;
  grid-row-end: 8;
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
  height:100%;
  width: 100%;
  opacity: 0;
  transition: .5s ease;
  background-color:white;
}

.overlay:hover {
  opacity: 0.7;
}

.overlay-text {
  color: black;
  font-size: 20px;
  font-family: 'Raleway', sans-serif;
  position: absolute;
  top: 50%;
  left: 50%;
  -webkit-transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50% -50%);
  text-align: center;
}

</style>