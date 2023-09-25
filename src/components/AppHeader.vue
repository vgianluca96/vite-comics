<script>

export default {
  name: 'AppHeader',
  data() {
    return {
      headerNavList: [
        {
          text: 'characters',
          active: false
        },
        {
          text: 'comics',
          active: true
        },
        {
          text: 'movies',
          active: false
        },
        {
          text: 'tv',
          active: false
        },
        {
          text: 'games',
          active: false
        },
        {
          text: 'collectibles',
          active: false
        },
        {
          text: 'fans',
          active: false
        },
        {
          text: 'news',
          active: false
        }, {
          text: 'shop',
          active: false
        }
      ]
    }
  }
}

</script>

<template>
  <header>

    <div class="container w-75 d-flex align-items-center justify-content-between p-0">

      <div class="d-flex">
        <img src="../assets/img/dc-logo.png" alt="">
      </div>

      <div class="d-flex justify-content-end">
        <div class="mx-2 py-5 text-uppercase fw-bold" v-for="item in headerNavList" :class="{ active: item.active }">
          <a href="javascript:void(0)">{{ item.text }}</a>
        </div>
      </div>

    </div>

  </header>
</template>

<style></style>
