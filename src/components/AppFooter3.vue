<script>

export default {
  name: 'AppFooter3',
  data() {
    return {
      socialLogos: [
        '../src/assets/img/footer-facebook.png',
        '../src/assets/img/footer-twitter.png',
        '../src/assets/img/footer-youtube.png',
        '../src/assets/img/footer-pinterest.png',
        '../src/assets/img/footer-periscope.png'
      ]
    }
  }
}

</script>

<template>
  <div class="footer3">
    <div class="container w-75 py-4 d-flex align-items-center justify-content-between">
      <div>
        <button>
          SIGN UP NOW!
        </button>
      </div>
      <div class="d-flex align-items-center justify-content-between">
        <div class="follow px-2 fw-bold">
          FOLLOW US
        </div>
        <div class="px-2" v-for="logo in socialLogos">
          <img :src="logo" alt="">
        </div>
      </div>

    </div>
  </div>
</template>

<style></style>
