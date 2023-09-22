<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter1 from './components/AppFooter1.vue'
import AppFooter2 from './components/AppFooter2.vue'

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter1,
    AppFooter2
  }
}
</script>


<template>
  <AppHeader />
  <AppMain />

  <footer>
    <AppFooter1 />
    <AppFooter2 />

    <div class="footer3">
      <div class="container w-75">
        <h1>ciao</h1>
      </div>
    </div>

  </footer>
</template>

<style lang="scss"></style>
