<template>
  <div class="container mx-auto flex flex-col w-full pb-10">
    <SectionHeader title="Kontakt" />
    <div class="flex flex-col w-full">
      <div class="flex w-full">
        <GoogleMap />
      </div>
      <div class="flex flex-col w-full full justify-evenly py-3">
        <div class="grid grid-cols-1 xl:grid-cols-3 gap-y-20">
          <div class="flex items-center flex-col prose-lg">
            <h3>Adresse:</h3>
            <div class="divider w-1/2"></div>
            <p class="text-center">
              Münsterstraße 3, 33104 Paderborn, Deutschland
            </p>
          </div>
          <div class="flex items-center flex-col prose-lg">
            <h3>Tel:</h3>
            <div class="divider w-1/2"></div>
            <a href="tel:+49157 356 645 999" class="btn red-button w-max my-5"
              >0157 356 645 99</a
            >
          </div>
          <div class="flex items-center flex-col prose-lg">
            <h3>E-mail:</h3>
            <div class="divider w-1/2"></div>
            <a
              href="mailto:mf-versiegelung@web.de"
              class="btn red-button w-max my-5 lowercase"
              >MF-VERSIEGELUNG@WEB.DE</a
            >
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import SectionHeader from '@/components/elements/SectionHeader'
export default {
  components: {
    SectionHeader,
  },
}
</script>

<style>
.red-button {
  background-color: red;
  transition: 0.2s ease-out;
}
.red-button:hover {
  background-color: crimson;
  transition: 0.2s ease-in;
}
</style>
