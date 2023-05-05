<template>
  <div>
    <ScrollNavbar />
    <section class="pt-16 pb-16">
      <slot />
    </section>
    <Footer />
  </div>
</template>

<script>
import ScrollNavbar from '@/components/ui/Navbar/ScrollNavbar.vue'
import Footer from '~/components/ui/Footer/Footer.vue'

export default {
  components: {
    ScrollNavbar,
    Footer
  }
}
</script>
