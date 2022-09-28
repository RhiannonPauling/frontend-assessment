<template>
  <div class="banner mb-4 text-center">
    <picture class="banner__img">
      <source media="(max-width: 600px)" srcset="https://via.placeholder.com/600x600" class="img-fluid" alt="Mobile banner placeholder"/>
      <img src="https://via.placeholder.com/1920x650" class="img-fluid" alt="Desktop banner placeholder"/>
    </picture>
    <div class="banner__text-area">
      <h1 class="banner__header mb-0">Hello Developer!</h1>
      <p class="banner__text">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'PageBanner',
}
</script>

<style lang="scss" scoped>
 @import '../assets/styles/banner.scss';
</style>