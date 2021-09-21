<template>
  <section>
    <SectionHeader title="Dienstleistungen" />
    <div
      class="container lg:px-5 grid gap-3 xl:grid-cols-2 md:grid-cols-1 mx-auto"
    >
      <div v-for="b in box">
        <Box :text="b.text" :img="b.img" />
      </div>
    </div>
  </section>
</template>

<script>
import Box from '@/components/elements/Box'
import SectionHeader from '@/components/elements/SectionHeader'
export default {
  components: {
    Box,
    SectionHeader,
  },
  data() {
    return {
      box: [
        {
          text: 'Dauerelastische Silikonversiegelungen',
          img: '/images/2.jpeg',
        },
        {
          text: 'Beton- & Klinkerfugen',
          img: '/images/8.jpeg',
        },
        {
          text: 'Fensteranschlussfugen',
          img: '/images/3.jpeg',
        },
        {
          text: 'Fugensanierung ',
          img: '/images/7.jpeg',
        },
        {
          text: 'Silikonfugen im Sanitär- & Innenbereich',
          img: '/images/4.jpeg',
        },
        {
          text: 'Farbpaletten',
          img: '/images/10.jpeg',
        },
      ],
    }
  },
}
</script>
