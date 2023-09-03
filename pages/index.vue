<template>
  <main>
    <HeroWeb />
    <AboutSection />
  </main>
</template>

<script>
// Memanggil component sesuai lokasi masing - masing file
import HeroWeb from '@/components/HeroWeb.vue'
import AboutSection from '@/components/AboutSection.vue'
export default {
  // Dideklarasikan agar dapat diakses oleh template
  components: {
    HeroWeb,
    AboutSection,
  },
  data() {
    return {
      // Daftar task
      about: [
        {
          icon: 'truck',
          title: 'Delivery Services',
        },
        {
          icon: 'arrow-right-arrow-left',
          title: 'Shipping & Return',
        },
        {
          icon: 'percent',
          title: 'Promotion',
        },
        {
          icon: 'user',
          title: '24 Hours Service',
        },
      ],
    }
  },
}
</script>
<style></style>
