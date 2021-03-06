<template>
  <nav class="nav">
    <div class="nav-mobile">
      <a href="#" class="nav-hamburger" @click.prevent="toggleMenu"><span></span></a>
    </div>
    <router-link class="nav-home" to="/">Nicolas Gabbani</router-link>
    <router-link to="/about">à propos de moi</router-link>
    <router-link to="/skills">compétences</router-link>
    <router-link to="/career">carrière</router-link>
    <router-link to="/contact">me contacter</router-link>
  </nav>
</template>

<script>
export default {
  name: 'Menu',
  setup() {
    const toggleMenu = () => document.querySelector('.nav').classList.toggle('active')

    return {
      toggleMenu
    }
  }
}
</script>