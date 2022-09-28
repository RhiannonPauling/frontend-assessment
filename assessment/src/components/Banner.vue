<template>
  <div class="content-container mb-3 text-center">
    <picture>
      <source media="(max-width: 600px)" srcset="https://via.placeholder.com/600x600" class="img-fluid" alt="Mobile banner placeholder"/>
      <img src="https://via.placeholder.com/1920x650" class="img-fluid" alt="Desktop banner placeholder"/>
    </picture>
    <div class="text">
      <h1 class="header">Hello Developer!</h1>
      <p>
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

<style scoped>
.content-container {
  position: relative;
  color: white;
}
.text {
  color: white;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
.header {
  font-weight: 900;
  font-size: 3rem;
}
p {
  font-size: 1.5rem;
}

</style>