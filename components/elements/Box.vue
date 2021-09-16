<template>
  <div class="card shadow-xl image-full">
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
.card:hover.image-full:before {
  background-color: transparent;
  transition: 0.2s ease-in-out;
}
.card.card-title {
  color: transparent;
}
</style>
