<template>
  <div>
    <h2 class="text-center md:text-5xl text-4xl py-14 font-bold">
      {{ title }}
    </h2>
  </div>
</template>

<script>
export default {
  name: 'SectionHeader',
  props: {
    title: '',
  },
}
</script>
