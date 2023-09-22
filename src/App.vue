<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter1 from './components/AppFooter1.vue'
import AppFooter2 from './components/AppFooter2.vue'
import AppFooter3 from './components/AppFooter3.vue'

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter1,
    AppFooter2,
    AppFooter3
  }
}
</script>


<template>
  <AppHeader />
  <AppMain />

  <footer>
    <AppFooter1 />
    <AppFooter2 />
    <AppFooter3 />

  </footer>
</template>

<style lang="scss"></style>
