<script>


export default {
  name: 'AppMain2Comics',
  data() {
    return {

    }
  },
  props: {
    thumb: String,
    series: String
  }
}

</script>

<template>
  <div class="col-4 col-md-3 col-lg-2 py-2">
    <div class="w-100 ratio ratio-1x1">
      <img :src="thumb" class="comic-img w-100" alt="...">
    </div>
    <div class="py-2 text-uppercase">
      <h6>{{ series }}</h6>
    </div>
  </div>
</template>

<style></style>
