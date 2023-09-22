<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  components: {
    HelloWorld
  },
  data() {
    return {
      message: 'Hello'
    }
  }

}
</script>

<template>
  <h1>
    <div>
      {{ message }}

    </div>
  </h1>

  <HelloWorld />


  <div class="card" style="width: 18rem;">

    <div class="card-body">
      <h5 class="card-title">Card title</h5>
      <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.
      </p>
      <a href="#" class="btn btn-primary">Go somewhere</a>
    </div>
  </div>
</template>

<style lang="scss"></style>
