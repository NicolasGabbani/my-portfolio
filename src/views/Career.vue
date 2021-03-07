<template>
  <div class="content" id="career">
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
    <div class="rellax rellax9" data-rellax-speed="6">
      <div class="polygon reverse smooth-blur"></div>
    </div>
    <div class="rellax rellax10" data-rellax-speed="6">
      <div class="polygon blur"></div>
    </div>
    <div class="rellax rellax11" data-rellax-speed="6">
      <div class="polygon blur"></div>
    </div>
    <h1>ma carrière</h1>
    <div class="sub-title">J'ai travaillé pour CareerBuilder pendant 6 ans.</div>
    <div>
      <div class="separator small-separator" data-aos="zoom-in-up" data-aos-offset="100">
        <div class="bg-img" :style="{ backgroundImage: `url(${require(`@/images/lesjeudis.jpg`)})` }"></div>
        <div class="bg-white">
          <h2><a href="https://www.lesjeudis.com/" target="_blank">LesJeudis.com</a></h2>
          <div class="society">careerbuilder</div>
          <p>
            <span class="tag">RoR</span>
            <span class="tag">jQuery</span>
            <span class="tag">Responsive</span>
            <span class="tag">UX/UI</span>
            <span class="tag">From Scratch</span>
          </p>
          <p>Site d'emploi spécialisé dans l'IT, mon rôle a été d'intégrer ce design à partir de maquettes sous la technologie RubyOnRails. Tout le code front-end est from-scratch et fait maison !</p>
          <h4>Missions :</h4>
          <ul>
            <li>Intégrateur/Développeur Front-End</li>
            <li>Optimisation et simplification du code, maintenance des solutions</li>
            <li>Designer pour la partie responsive du site</li>
          </ul>
        </div>
      </div>
      <div class="separator" data-aos="zoom-in-up" data-aos-offset="-100">
        <div class="bg-img" :style="{ backgroundImage: `url(${require(`@/images/jobmedic.jpg`)})` }"></div>
        <div class="bg-white">
          <h2><a href="https://www.jobmedic.co.uk/" target="_blank">jobmedic.co.uk</a></h2>
          <div class="society">careerbuilder</div>
          <p>
            <span class="tag">RoR</span>
            <span class="tag">jQuery</span>
            <span class="tag">Responsive</span>
            <span class="tag">UX/UI</span>
            <span class="tag">From Scratch</span>
          </p>
          <p>Job-board destiné aux métiers médicaux, j'ai pensé et designé (UI et UX) la première version du site entièrement en mobile first. <br> J'ai ensuite intégré le tout from scratch tout en apportant des améliorations quotidiennes. <br> Le design a peu à peu changé pour coller à celui du site principal de la société careerbuilder.com auquel j'ai aussi très activement participé.</p>
          <h4>Missions :</h4>
          <ul>
            <li>Intégrateur et UI/UX designer</li>
            <li>Optimisation et simplification du code, maintenance des solutions et expertise design (UI et UX)</li>
          </ul>
        </div>
      </div>
      <div class="separator" data-aos="zoom-in-up" data-aos-offset="-100">
        <div class="bg-img" :style="{ backgroundImage: `url(${require(`@/images/careerbuilder.png`)})` }"></div>
        <div class="bg-white">
          <h2><a href="https://www.careerbuilder.com/" target="_blank">careerbuilder.com</a></h2>
          <div class="society">careerbuilder</div>
          <p>
            <span class="tag">RoR</span>
            <span class="tag">jQuery</span>
            <span class="tag">Responsive</span>
            <span class="tag">UX/UI</span>
            <span class="tag">From Scratch</span>
          </p>
          <p>Site principal de la société Careerbuilder, j'ai participé activement au design en me basant sur l'expérience acquise sur le projet jobmedic. Je l'ai ensuite intégré entièremment en continuant à être force de proposition tout le long du projet. <br> L'équipe étant internationale, la communication s'effectuait en anglais.</p>
          <h4>Missions :</h4>
          <ul>
            <li>Intégrateur et UI/UX designer</li>
            <li>Optimisation et simplification du code, maintenance des solutions et expertise design (UI et UX)</li>
            <li>Présentation live hebdomadaire aux PO/Staff en anglais</li>
          </ul>
        </div>
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
  }
}
</script>

<style lang="sass" scoped>
  .design-circle
    background: var(--color-five)
  .separator:last-child
    margin-bottom: 100px
  .bg-img
    height: 350px
    width: 100%
    border-radius: 10px
    
    background-repeat: no-repeat
    background-size: cover
    background-position: center center
  .society
    color: grey
    text-transform: uppercase
    font-size: .8rem
    margin-bottom: 10px
  .bg-white
    background-color: var(--color-white)
    box-shadow: 0 0 25px 5px rgba(0,0,0,.4)

    width: 30vw
    margin: -300px auto 0 auto
    padding: 30px
    position: relative

    border-radius: 10px
    h4
      margin-bottom: 10px
    .tag
      margin-right: 4px 
      &:last-child
        margin-right: 0
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
  .rellax9
    position: absolute
    bottom: -150%
    right: 10%
    .polygon
      animation-delay: 1.5s
  .rellax10
    position: absolute
    bottom: -170%
    left: 10%
    .polygon
      animation-delay: .5s
  .rellax11
    position: absolute
    bottom: -180%
    left: 13%
    .polygon
      animation-delay: 1s
</style>