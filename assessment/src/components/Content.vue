<template>
  <div class="container card-deck content">
    <div class="row row-cols-1 row-cols-xs-1 row-cols-md-3 g-3">
      <div class="col">
        <div class="card h-100 content__item">
          <img class="card-image-top content__img" src="https://via.placeholder.com/400x300" alt="Content Image"/>
          <div class="flex-column d-flex card-body align-items-center content__text-area">
            <p class="card-text content__text">
              Lorem insum dolor sit amet, consectetur adioiscing elit, sed do eiusmod tempor incididunt ut labore et dolore maana alaua. Ut enim ad
              minim veniam, guis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
            </p>
            <button class="pb-1 pt-2 px-3 mt-auto border-2 border-dark bg-white text-uppercase content__button">Read More</button>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card h-100 content__item">
          <img class="card-image-top content__img" src="https://via.placeholder.com/400x300" alt="Content Image"/>
          <div class="flex-column d-flex card-body align-items-center content__text-area">
            <p class="card-text content__text">
              Lorem losum door sir amen consectetur adioiscina elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
            </p>
            <button class="pb-1 pt-2 px-3 mt-auto border-2 border-dark bg-white text-uppercase content__button">Read More</button>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card h-100 content__item">
          <img class="card-image-top content__img" src="https://via.placeholder.com/400x300" alt="Content Image"/>
          <div class="flex-column d-flex card-body align-items-center content__text-area">
            <p class="card-text content__text">
              Lorem losum door si amen, consectetur adioiscina elit, sed do eiusmod tempor incididunt ut labore et dolore maana alaua. Ut enim 20
              minim veniam, quis nostrud exercilalon illamco.
            </p>
            <button class="pb-1 pt-2 px-3 mt-auto border-2 border-dark bg-white text-uppercase content__button">Read More</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'PageContent',
}
</script>

<style lang="scss" scoped>
  @import '../assets/styles/content.scss';
</style>
