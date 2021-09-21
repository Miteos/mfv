<template>
  <div
    class="hero min-h-screen bg-cover overflow-x-hidden"
    style="background-image: url('/images/image.jpg')"
  >
    <div class="hero-overlay bg-opacity-30"></div>
    <div class="text-center hero-content text-neutral-content">
      <div class="max-w-xl">
        <AnimatedTitle />
        <h1 class="mt-10 pb-40 lg:mt-40 lg:text-5xl text-3xl font-bold">
          MFV Versiegelung
        </h1>
        <p class="mb-5 2xl:text-3xl md:text-lg lg:text-xl">
          Wenn nicht stehe ich Ihnen kurzfristig zur Verfügung!
        </p>
        <a href="tel:+49157 356 645 999" class="btn w-max my-5 red-button"
          >0157 356 645 99</a
        >
      </div>
    </div>
  </div>
</template>

<script>
import AnimatedTitle from '@/components/elements/AnimatedTitle'
export default {
  components: {
    AnimatedTitle,
  },
}
</script>
<style>
.hero-content {
  max-height: 200rem !important;
  min-height: 50rem;
}
.hero {
  /*background-position: bottom;*/
  background-repeat: no-repeat;
}
@media screen and (max-width: 640px) {
  .hero {
    background-position: 43% 55%;
    background-repeat: no-repeat;
  }
}
@media screen and (max-width: 350px) {
  .hero-content {
    min-height: 100vh;
  }
}
.red-button {
  background-color: red;
  transition: 0.2s ease-out;
}
.red-button:hover {
  background-color: crimson;
  transition: 0.2s ease-in;
}
</style>
