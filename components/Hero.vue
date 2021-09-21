<template>
  <div
    class="hero min-h-screen bg-cover overflow-x-hidden"
    style="background-image: url('/images/hero-5-min.jpg')"
  >
    <div class="hero-overlay bg-opacity-30"></div>
    <div class="text-center hero-content text-neutral-content">
      <div class="max-w-xl">
        <h1 class="mb-20 lg:text-5xl text-3xl font-bold">MFV Versiegelung</h1>
        <p class="mb-5 text-4xl 2xl:font-bold">Alles dicht?</p>
        <p class="mb-5 2xl:text-2xl md:text-lg lg:text-xl">
          Wenn nicht stehe ich Ihnen kurzfristig zur Verfügung!
        </p>
        <a
          href="tel:+49157 356 645 999"
          class="btn w-max my-5 bg-secondary hover:bg-secondary-focus"
          >0157 356 645 99</a
        >
      </div>
    </div>
  </div>
</template>

<script></script>
<style>
.hero-content {
  max-height: 200rem !important;
}
.hero {
  background-position: bottom;
}
@media screen and (max-width: 640px) {
  .hero {
    background-position: 60%;
    background-repeat: no-repeat;
  }
}
</style>
