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
    z-index: 5

    background: var(--color-green)

    animation: floating 6s ease-in-out infinite
    
.itsme-desc
  display: block

  margin-top: 10px

  font-size: 2rem
  font-family: var(--font-dancing)
</style>
