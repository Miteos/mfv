<template>
  <div style="height: 100%; width: 100%">
    <iframe
      :src="`https://maps.google.com/maps?q=51.742390,8.708633&z=18&amp;output=embed`"
      class="google-map"
      frameborder="0"
      allowfullscreen=""
      aria-hidden="false"
      tabindex="0"
    ></iframe>
  </div>
</template>

<style>
.google-map {
  display: block;
  width: 100%;
  height: 400px;
  padding: 20px 0;
}
</style>
