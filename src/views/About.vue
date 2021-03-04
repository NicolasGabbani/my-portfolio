<template>
  <div class="content">
    <div class="design-circle"></div>
    <div class="rellax rellax1" data-rellax-speed="7">
      <div class="polygon reverse blur"></div>
    </div>
    <div class="rellax rellax2" data-rellax-speed="4">
      <div class="polygon smooth-blur"></div>
    </div>
    <div class="rellax rellax3" data-rellax-speed="9">
      <div class="polygon blur"></div>
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
    <div class="grid" data-aos="zoom-in-up" data-aos-offset="100">
      <div class="col">
        <lottie-player class="lottie" src="https://assets2.lottiefiles.com/packages/lf20_rycdh53q.json"  background="transparent"  speed="1"  loop  autoplay></lottie-player>
      </div>
      <div class="col">
        <h2>Bosseur !</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Omnis deserunt laboriosam dolor, mollitia sequi molestiae cum voluptate, vitae illo sit inventore quae, blanditiis incidunt vero quod tenetur architecto earum accusamus. Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi id asperiores ut repudiandae quas rerum recusandae fugit possimus vitae ea explicabo autem quod nihil iure, fuga libero accusantium unde velit!</p>
      </div>
    </div>
    <div class="grid separator" data-aos="zoom-in-up" data-aos-offset="100">
      <div class="col">
        <h2>Teamwork !</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit quod veritatis ipsum, minima ea eaque provident temporibus! Veritatis eligendi perspiciatis, architecto voluptatibus at ipsum odio neque fugit cum consequuntur sit.</p>
      </div>
      <div class="col">
        <lottie-player class="lottie" src="https://assets10.lottiefiles.com/private_files/lf30_abpsfqg6.json"  background="transparent"  speed="1" loop  autoplay></lottie-player>
      </div>
    </div>
    <div class="grid" data-aos="zoom-in-up" data-aos-offset="100">
      <div class="col">
        <lottie-player class="lottie" src="https://assets4.lottiefiles.com/packages/lf20_3JZqqW.json"  background="transparent"  speed="1"  loop  autoplay></lottie-player>
      </div>
      <div class="col">
        <h2>Auto didacte !</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. At quia voluptatum libero sapiente quas. Quae illo, alias sapiente repellendus distinctio excepturi dolorem, sed voluptas consequatur, repellat aliquam blanditiis cumque reiciendis!</p>
      </div>
    </div>
  </div>
</template>

<script>
import AOS from 'aos'
import 'aos/dist/aos.css'
import Rellax from 'rellax'
export default {
  mounted() {
    AOS.init()
    new Rellax('.rellax')
  },
}
</script>

<style lang="sass">
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
  .rellax3
    position: absolute
    top: 30%
    left: 13%
  .rellax4
    position: absolute
    bottom: -30%
    left: 10%
  .rellax5
    position: absolute
    bottom: -70%
    left: 14%
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