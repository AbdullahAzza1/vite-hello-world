<script>
import AppTitle  from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'

export default {
  components: {
    AppTitle,
    AppHero
  }
}
</script>

<template>
  <div>
    Benvenuto nella tua App in Vue.js
  </div>
  <AppTitle />
  <AppHero />
</template>

<style scoped></style>
