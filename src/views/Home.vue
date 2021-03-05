<template>
  <div class="home">
    <div class="polygon reverse polygon-html">REACT</div>
    <div class="polygon polygon-css">AGILE</div>
    <div class="polygon reverse polygon-js">VUEJS</div>
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
    <h1 class="itsme">Nicolas <span>Gabbani</span> <div class="i"></div> <div class="i-hidden"></div></h1>
    <span class="itsme-desc">Développeur Front-End</span>
    <router-link class="cta" to="/about">me découvrir</router-link>
  </div>
</template>

<script>
export default {
  name: 'Home',
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
  .i, .i-hidden
    display: block

    width: 20px
    height: 20px

    border-radius: 50%
    background: var(--color-one)

    position: absolute
    top: 16%
    right: 0
  .i
    top: 14%
    right: 1px
    z-index: 5

    width: 18px
    height: 18px

    background: var(--color-green)

    animation: floating 6s ease-in-out infinite
    
.itsme-desc
  display: block

  margin-top: 10px

  font-size: 2rem
  font-family: var(--font-dancing)

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
