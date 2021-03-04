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
  setup() {
    return {
      Menu
    }
  }
}
</script>
