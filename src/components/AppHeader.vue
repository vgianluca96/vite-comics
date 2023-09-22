<script>

export default {
  name: 'AppHeader',
  data() {
    return {
      listItems: [
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

    <nav class="container w-75 d-flex align-items-center px-0 py-2">

      <div class="col-4 d-flex justify-content-center">
        <img src="../assets/img/dc-logo.png" alt="">
      </div>

      <div class="col-8 d-flex justify-content-center">
        <ul class="text-uppercase list-group list-group-horizontal">

          <li class="px-2 fw-bold" v-for="item in listItems">
            <a href="javascript:void(0)">{{ item }}</a>
          </li>
        </ul>

      </div>

    </nav>

  </header>
</template>

<style></style>
