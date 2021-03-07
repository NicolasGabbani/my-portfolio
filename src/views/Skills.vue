<template>
  <div class="content" id="skills">
    <div class="design-circle"></div>
    <div class="polygon polygon1 reverse blur"></div>
    <div class="polygon polygon2 blur"></div>
    <div class="polygon polygon3 blur"></div>
    <h1>Mes compétences</h1>
    <div class="sub-title">J'avoue, j'ai une préférence pour VueJS...</div>
    <div class="grid separator" data-aos="zoom-in-up" data-aos-offset="100">
      <div class="col">
        <lottie-animation path="json/skill.json" :loop="true" :autoPlay="true" :speed="1" />
      </div>
      <div class="col">
        <h2>Les bases !</h2>
        <p>Sans surprises, je maitrîse parfaitement <b>HTML5</b> et <b>CSS3/SASS</b> en m'appuyant sur des techniques modernes (et bien pratiques).</p>
        <p>D'un naturel curieux et toujours à la recherche de l'excellence, je continue à me former constamment sur les nouvelles technologies sur le marché comme <b>Vuejs</b> ou <b>React</b> tout en maintenant un excellent niveau en <b>javascript ES6</b> et <b>jQuery</b>.</p>
        <p>
          <span class="tag">HTML5/HAML</span> <span class="tag">CSS3/SASS/SCSS/LESS</span> <span class="tag">JS/jQuery</span>
        </p>
      </div>
    </div>
    <div class="separator">
      <h2>Mes autres compétences</h2>
      <div class="full-grid skills">
        <div class="col">
          <span class="tag big-tag">vuejs</span>
        </div>
        <div class="col">
          <span class="tag big-tag">UX/UI</span>
        </div>
        <div class="col">
          <span class="tag big-tag">Responsive</span>
        </div>
        <div class="col">
          <span class="tag big-tag">Cross Browser</span>
        </div>
        <div class="col">
          <span class="tag big-tag">Github/Gitlab</span>
        </div>
        <div class="col">
          <span class="tag big-tag">react</span>
        </div>
        <div class="col">
          <span class="tag big-tag">WebDesign</span>
        </div>
        <div class="col">
          <span class="tag big-tag">Bootstrap</span>
        </div>
        <div class="col">
          <span class="tag big-tag">phaser</span>
        </div>
        <div class="col">
          <span class="tag big-tag">RubyOnRails</span>
        </div>
        <div class="col col-end">
          <span class="small">et tant d'autres...</span>
        </div>
      </div>
    </div>
    <div>
      <h2>mes plugins javascript préférés</h2>
      <div class="full-grid skills">
        <div class="col">
          <span class="tag big-tag">owl carousel</span>
        </div>
        <div class="col">
          <span class="tag big-tag">animejs</span>
        </div>
        <div class="col">
          <span class="tag big-tag">rellax</span>
        </div>
        <div class="col">
          <span class="tag big-tag">tsparticle</span>
        </div>
        <div class="col">
          <span class="tag big-tag">lottiefiles</span>
        </div>
        <div class="col">
          <span class="tag big-tag">animate on scroll</span>
        </div>
        <div class="col">
          <span class="tag big-tag">progressbar</span>
        </div>
        <div class="col">
          <span class="tag big-tag">tilt</span>
        </div>
        <div class="col">
          <span class="tag big-tag">numeraljs</span>
        </div>
        <div class="col">
          <span class="tag big-tag">simplebar</span>
        </div>
        <div class="col col-end">
          <span class="small">et tant d'autres...</span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import AOS from 'aos'
import 'aos/dist/aos.css'
import LottieAnimation from "lottie-vuejs/src/LottieAnimation.vue"
export default {
  name: 'Skills',
  mounted() {
    AOS.init()
  },
  setup() {
    return {
      LottieAnimation
    }
  }
}
</script>

<style lang="sass" scoped>
  .design-circle
    background: var(--color-three)
    opacity: .1
  .skills
    .col
      animation: zoomIn var(--transition-duration) ease forwards
      transform: scale(0)
  @for $i from 1 through 8
    .skills .col:nth-child(#{$i}n)
      animation-delay: #{$i * 0.1}s
  .polygon1
    position: absolute
    top: 16%
    left: 20%
  .polygon2
    position: absolute
    top: 10%
    left: 24%
    animation-delay: 1s
  .polygon3
    position: absolute
    top: 14%
    right: 30%
    animation-delay: .5s
  .col-end
    grid-column-start: 5
    text-align: right
</style>
