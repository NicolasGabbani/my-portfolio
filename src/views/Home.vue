<template>
  <div class="home">
    <div class="polygon reverse polygon-react">REACT</div>
    <div class="polygon polygon-agile">AGILE</div>
    <div class="polygon reverse polygon-vuejs">VUEJS</div>
    <div class="polygon polygon-design">UX/UI</div>
    <div class="polygon-empty polygon-empty1">
      <div class="polygon"></div>
    </div>
    <div class="polygon-empty polygon-empty2">
      <div class="polygon"></div>
    </div>
    <div class="polygon-empty polygon-empty3">
      <div class="polygon reverse"></div>
    </div>
    <h1 class="itsme">{{data.firstname}} <span>{{data.lastname}}</span></h1>
    <span class="itsme-desc">Développeur Front-End</span>
    <router-link class="cta" to="/about">me découvrir</router-link>
  </div>
</template>

<script>
export default {
  name: 'Home',
  setup() {
    const data = {
      firstname: 'Nicolas',
      lastname: 'Gabbani',
    }

    return {
      data
    }
  }
}
</script>

<style lang="sass">
.home
  display: flex
  justify-content: center
  align-items: center
  flex-direction: column

  position: relative

  height: 100vh

.itsme
  font-family: var(--font-righ)
  font-size: 5rem
  position: relative
  span
    color: var(--color-green)
    
.itsme-desc
  display: block

  margin-top: 10px

  font-size: 2rem
  font-family: var(--font-dancing)

.polygon-react
  top: 30%
  left: 30%

.polygon-agile
  top: 35%
  right: 30%
  animation-delay: 1s

.polygon-vuejs
  bottom: 30%
  right: 40%
  animation-delay: 1.5s

.polygon-design
  bottom: 40%
  left: 25%
  animation-delay: 1.2s

.polygon-empty
  position: absolute
  z-index: -1
  
.polygon-empty1
  top: 30%
  transform: scale(.4)
  filter: blur(4px)

.polygon-empty2
  bottom: 35%
  right: 35%
  transform: scale(.6)
  filter: blur(4px)

.polygon-empty3
  bottom: 30%
  left: 35%
  transform: scale(.3)
  filter: blur(12px)

.cta
  display: block
  margin-top: 50px
  padding: 12px 18px 8px 18px

  font-size: 1.4rem
  //text-transform: uppercase
  font-weight: bold
  font-family: var(--font-indie)
  line-height: 1

  color: var(--color-green)
  background: rgba(0, 128, 101, .1)
  border-radius: 30px

  transition: all var(--transition-duration)

  &:hover
    background: rgba(0, 128, 101, .2)
</style>
