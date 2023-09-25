<script>
import AppHeader from './components/AppHeader.vue'
import AppMain1 from './components/AppMain1.vue'
import AppMain2 from './components/AppMain2.vue'
import AppFooter1 from './components/AppFooter1.vue'
import AppFooter2 from './components/AppFooter2.vue'
import AppFooter3 from './components/AppFooter3.vue'

export default {
  components: {
    AppHeader,
    AppMain1,
    AppMain2,
    AppFooter1,
    AppFooter2,
    AppFooter3
  }
}
</script>


<template>
  <AppHeader />

  <main>
    <AppMain1 />
    <AppMain2 />
  </main>

  <footer>
    <AppFooter1 />
    <AppFooter2 />
    <AppFooter3 />
  </footer>
</template>

<style lang="scss"></style>
