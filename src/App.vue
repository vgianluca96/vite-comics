<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter1 from './components/AppFooter1.vue'

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter1
  }
}
</script>


<template>
  <AppHeader />
  <AppMain />

  <footer>
    <AppFooter1 />

  </footer>
</template>

<style lang="scss"></style>
