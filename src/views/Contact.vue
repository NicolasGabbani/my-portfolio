<template>
  <div class="content">
    <div class="polygon polygon1 blur"></div>
    <div class="polygon polygon2 blur"></div>
    <div class="polygon polygon3 reverse blur"></div>
    <div class="design-circle"></div>
    <h1>me contacter</h1>
    <div class="sub-title">Allo ? Bonjour, vous allez bien ? :)</div>
    <div class="grid separator" data-aos="zoom-in-up" data-aos-offset="100">
      <div class="col">
        <lottie-animation path="json/contact.json" :loop="true" :autoPlay="true" :speed="1" />
      </div>
      <div class="col">
        <p>Si mon profil vous intéresse,  n'hésitez pas à me contacter ! Je serais ravi d'échanger avec vous, c'est toujours enrichissant !</p>
        <div class="p">
          <a target="_blank" href="https://www.linkedin.com/in/nicolas-gabbani/" class="btn">Linkedin</a>
          <a href="mailto:nicolasgabbani@gmail.com" class="btn">nicolasgabbani@gmail.com</a>
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

<style lang="sass">
  .design-circle
    background: var(--color-four)
    opacity: .1
  .polygon1
    position: absolute
    top: 40%
    left: 15%
  .polygon2
    position: absolute
    top: 10%
    right: 24%
    animation-delay: 1s
  .polygon3
    position: absolute
    bottom: 5%
    right: 10%
    animation-delay: .5s
</style>