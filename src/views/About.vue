<template>
  <div class="content" id="about">
    <div class="design-circle"></div>
    <div class="rellax rellax1" data-rellax-speed="7">
      <div class="polygon reverse blur"></div>
    </div>
    <div class="rellax rellax2" data-rellax-speed="4">
      <div class="polygon smooth-blur"></div>
    </div>
    <div class="rellax rellax4" data-rellax-speed="7">
      <div class="polygon reverse blur"></div>
    </div>
    <div class="rellax rellax5" data-rellax-speed="4">
      <div class="polygon smooth-blur"></div>
    </div>
    <div class="rellax rellax6" data-rellax-speed="2">
      <div class="polygon reverse blur"></div>
    </div>
    <div class="rellax rellax7" data-rellax-speed="9">
      <div class="polygon blur"></div>
    </div>
    <div class="rellax rellax8" data-rellax-speed="9">
      <div class="polygon reverse smooth-blur"></div>
    </div>
    <h1>À PROPOS DE MOI</h1>
    <div class="sub-title">Pas peu fier d'être autodidacte !</div>
    <div>
      <div class="grid separator small-separator" data-aos="zoom-in-up" data-aos-offset="100">
        <div class="col">
          <lottie-animation path="json/investi.json" :loop="true" :autoPlay="true" :speed="1" />
        </div>
        <div class="col">
          <h2>Investi !</h2>
          <p>Toujours la tête dans le cloud et en veille technologique, je cherche toujours à avoir une plus-value dans mes intégrations pour réaliser des produits à l'effet "wow".</p>
          <p>J'aime travailler avec les méthodes agiles pour être plus efficace dans mon organisation.</p>
          <p>
            <span class="tag">pixel perfect</span> <span class="tag">responsive design</span> <span class="tag">clean code</span> <span class="tag">scrum</span>
          </p>
        </div>
      </div>
      <div class="grid separator" data-aos="zoom-in-up" data-aos-offset="100">
        <div class="col">
          <h2>Teamwork !</h2>
          <p>En tant que développeur front-end, je prends plaisir à travailler avec l'ensemble d'une équipe pour mener à bien des projets alliant technicité et sensibilité.</p>
          <p>Force de proposition, j'aime apporter des conseils et partager mon expérience pour le bien d'un projet et, bien sûr, m'enrichir des autres.</p>
          <p>
            <span class="tag">peer coding</span> <span class="tag">inspirant</span> <span class="tag">méthodes agiles</span>
          </p>
        </div>
        <div class="col col-responsive-first">
          <lottie-animation path="json/teamwork.json" :loop="true" :autoPlay="true" :speed="1" />
        </div>
      </div>
      <div class="grid separator small-separator" data-aos="zoom-in-up" data-aos-offset="100">
        <div class="col">
          <lottie-animation path="json/autodidacte.json" :loop="true" :autoPlay="true" :speed="1" />
        </div>
        <div class="col">
          <h2>Autodidacte !</h2>
          <p>Passionné depuis toujours, j'ai décidé, il y a maintenant 6 ans, de faire d'internet mon métier. <br> Ma curiosité naturelle m'a amené à apprendre tout ce que je pouvais sur le développement web.</p>
          <p>Pourquoi être devenu Développeur Front-End ? J'aime quand une maquette prend vie.</p>
          <p>
            <span class="tag">try hard</span> <span class="tag">indépendant</span> <span class="tag">challenger</span>
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import AOS from 'aos'
import 'aos/dist/aos.css'
import Rellax from 'rellax'
import LottieAnimation from "lottie-vuejs/src/LottieAnimation.vue"
export default {
  mounted() {
    AOS.init()
    new Rellax('.rellax')
  },
  setup() {
    return {
      LottieAnimation
    }
  }
}
</script>

<style lang="sass">
  .separator:last-child
    margin-bottom: 100px
  .rellax1
    position: absolute
    bottom: 30%
    left: 15%
  .rellax2
    position: absolute
    bottom: 25%
    left: 17%
    .polygon
      animation-delay: 1s
  .rellax4
    position: absolute
    bottom: -30%
    left: 10%
  .rellax5
    position: absolute
    bottom: -30%
    right: 14%
    .polygon
      animation-delay: 1s
  .rellax6
    position: absolute
    top: 35%
    right: 13%
  .rellax7
    position: absolute
    bottom: 0
    right: 18%
  .rellax8
    position: absolute
    bottom: -70%
    right: 13%
    .polygon
      animation-delay: 1s
</style>