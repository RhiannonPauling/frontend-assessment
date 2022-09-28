<template>
  <div class="container card-deck">
    <div class="row row-cols-1 row-cols-xs-1 row-cols-md-3 g-3">
      <div class="col">
        <div class="card h-100 shadow-sm">
          <img class="card-image-top" src="https://via.placeholder.com/400x300" alt="Content Image"/>
          <div class="flex-column d-flex card-body align-items-center">
            <p class="card-text">
              Lorem insum dolor sit amet, consectetur adioiscing elit, sed do eiusmod tempor incididunt ut labore et dolore maana alaua. Ut enim ad
              minim veniam, guis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
            </p>
            <button class="pb-1 pt-2 px-3 mt-auto border-2 border-dark bg-white text-uppercase">Read More</button>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card h-100 shadow-sm">
          <img class="card-image-top" src="https://via.placeholder.com/400x300" alt="Content Image"/>
          <div class="flex-column d-flex card-body align-items-center">
            <p class="card-text">
              Lorem losum door sir amen consectetur adioiscina elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
            </p>
            <button class="pb-1 pt-2 px-3 mt-auto border-2 border-dark bg-white text-uppercase">Read More</button>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card h-100 shadow-sm">
          <img class="card-image-top" src="https://via.placeholder.com/400x300" alt="Content Image"/>
          <div class="flex-column d-flex card-body align-items-center">
            <p class="card-text">
              I orem losum door si amen, consectetur adioiscina elit, sed do eiusmod tempor incididunt ut labore et dolore maana alaua. Ut enim 20
              minim veniam, quis nostrud exercilalon illamco.
            </p>
            <button class="pb-1 pt-2 px-3 mt-auto border-2 border-dark bg-white text-uppercase">Read More</button>
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

<style scoped>
  .container {
    margin-bottom: 2rem;
  }
  .card {
    margin: 0.5rem;
    padding: 1rem;
    border-radius: 0.25rem;
  }
  button {
    max-width: 9rem;
    border-radius: 1rem;
    font-size: 0.7rem;
    font-weight: 700;
    letter-spacing: 2px;
  }
  .card-body {
    padding: 0;
  }
  img {
    border-radius: 0.25rem;
    margin-bottom: 1rem;
  }
</style>
