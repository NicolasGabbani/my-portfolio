<template>
  <Menu />
  <router-view v-slot="{ Component }">
    <transition name="fade" mode="out-in">
      <component :is="Component" />
    </transition>
  </router-view>
</template>

<style lang="sass" src="./sass/app.sass"></style>

<script>
import Menu from '@/components/Menu'
export default {
  watch:{
    $route (){
      document.querySelector('.nav').classList.remove('active')
    }
  },
  setup() {
    return {
      Menu
    }
  }
}
</script>
