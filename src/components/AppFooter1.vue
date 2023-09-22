<script>

export default {
  name: 'AppFooter1',
  data() {
    return {
      footerItems: [
        {
          image: '../src/assets/img/buy-comics-digital-comics.png',
          text: 'digital comics'
        },
        {
          image: '../src/assets/img/buy-comics-merchandise.png',
          text: 'dc merchandise'
        },
        {
          image: '../src/assets/img/buy-comics-subscriptions.png',
          text: 'subscription'
        },
        {
          image: '../src/assets/img/buy-comics-shop-locator.png',
          text: 'comic shop locator'
        },
        {
          image: '../src/assets/img/buy-dc-power-visa.svg',
          text: 'dc power visa'
        },
      ]
    }
  }
}

</script>

<template>
  <div class="footer1">

    <div class="container w-75 py-4 d-flex align-items-center justify-content-between">

      <div class="col-2 d-flex align-items-center justify-content-between text-uppercase" v-for="item in footerItems">

        <div class="col-5 px-2">
          <img :src="item.image" alt="" class="w-100">
        </div>
        <div class="ps-1">
          {{ item.text }}
        </div>

      </div>

    </div>

  </div>
</template>

<style></style>
