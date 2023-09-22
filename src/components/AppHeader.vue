<script>

export default {
  name: 'AppHeader',
  data() {
    return {
      headerNavList: [
        'characters',
        'comics',
        'movies',
        'tv',
        'games',
        'collectibles',
        'fans',
        'news',
        'shop'
      ]
    }
  }
}

</script>

<template>
  <header>

    <nav>

      <div class="container w-75 d-flex align-items-center justify-content-between py-2">
        <div class="d-flex">
          <img src="../assets/img/dc-logo.png" alt="">
        </div>

        <div class="d-flex justify-content-end">
          <ul class="text-uppercase list-group list-group-horizontal">

            <li class="px-3 fw-bold" v-for="item in headerNavList">
              <a href="javascript:void(0)">{{ item }}</a>
            </li>

          </ul>

        </div>
      </div>


    </nav>

  </header>
</template>

<style></style>
