<script>
import DCcomics from '../comics.json';

export default {
  name: 'AppMain2',
  data() {
    return {
      comics: DCcomics
    }
  }
}

</script>

<template>
  <div class="container w-75 py-4">

    <h4>
      <span class="badge bg-primary">CURRENT SERIES</span>
    </h4>

    <div class="row">
      <div class="col-4 col-md-3 col-lg-2 py-2" v-for="comic in comics">
        <div class="w-100 ratio ratio-1x1">
          <img :src="comic.thumb" class="comic-img w-100" alt="...">
        </div>
        <div class="py-2 text-uppercase">
          <h6>{{ comic.series }}</h6>
        </div>
      </div>
    </div>

    <div class="d-flex justify-content-center">
      <button class="btn btn-primary fw-bold">
        LOAD MORE
      </button>
    </div>

  </div>
</template>

<style></style>
