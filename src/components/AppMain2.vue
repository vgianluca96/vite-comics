<script>
import comics from '../comics.json';
import AppMain2Comics from './AppMain2Comics.vue';

export default {
  name: 'AppMain2',
  data() {
    return {
      comics
    }
  },
  components: {
    AppMain2Comics
  }
}

</script>

<template>
  <div class="main2 container w-75 py-5">

    <div class="current">
      <span class="badge bg-primary rounded-0">CURRENT SERIES</span>
    </div>

    <div class="row">
      <AppMain2Comics :thumb="comic.thumb" :series="comic.series" v-for="comic in comics" />
    </div>

    <div class="d-flex justify-content-center">
      <button class="btn btn-primary fw-bold rounded-0">
        LOAD MORE
      </button>
    </div>

  </div>
</template>

<style></style>
