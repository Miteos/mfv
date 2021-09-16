<template>
  <div class="card shadow-xl mx-4 lg:mx-0 image-full">
    <figure>
      <img :src="img" alt="image" />
    </figure>
    <div class="justify-start card-body">
      <h2 class="card-title">{{ text }}</h2>
    </div>
  </div>
</template>
<script>
export default {
  name: 'Box',
  props: {
    text: '',
    img: '',
  },
}
</script>

<style>
.card {
  max-height: 400px;
  transition: 0.3s ease-out;
}
@media screen and (max-width: 640px) {
  .card {
    max-height: 300px;
  }
}
.card img {
  background-size: contain;
}
.card:hover.image-full {
  transition: 0.2s ease-in-out;
  box-shadow: 0 1px 10px 0 #bd0091 !important;
}
.card.image-full:before {
  background-color: transparent;
}
.card.card-title {
  color: transparent;
}
</style>
