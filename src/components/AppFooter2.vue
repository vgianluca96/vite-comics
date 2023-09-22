<script>

export default {
  name: 'AppFooter2',
  data() {
    return {
      footerList: [
        {
          title: 'DC COMICS',
          list: [
            'Characters',
            'Comics',
            'Movies',
            'TV',
            'Games',
            'Videos',
            'News'
          ]
        },
        {
          title: 'SHOPS',
          list: [
            'Shop DC',
            'Shop DC Collections'
          ]
        },
        {
          title: 'DC',
          list: [
            'Terms Of Use',
            'Privacy Policy (New)',
            'Ad Choices',
            'Advertising',
            'Jobs',
            'Subscriptions',
            'Talent Workshops',
            'CPSC Certificates',
            'Ratings',
            'Shop Help',
            'Contact Us'
          ]
        },
        {
          title: 'SITES',
          list: [
            'DC',
            'MAD Magazine',
            'DC Kids',
            'DC Universe',
            'DC Power Visa'
          ]
        }
      ]
    }
  }
}

</script>

<template>
  <div class="footer2">

    <div class="footer2-container container w-75 py-4 d-flex align-items-center justify-content-between">

      <div class="link-container d-flex flex-column flex-wrap">

        <div class="p-2" v-for="item in footerList">

          <h3 class="text-light">{{ item.title }}</h3>

          <ul class="list-unstyled">

            <li class="" v-for="item1 in item.list">
              <a href="javascript:void(0)">{{ item1 }}</a>
            </li>

          </ul>

        </div>

      </div>

      <div>
        <img src="../assets/img/dc-logo-bg.png" alt="">
      </div>

    </div>

  </div>
</template>

<style></style>
