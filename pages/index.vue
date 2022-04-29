<template>
  <div>
    <!-- ======= Header ======= -->
    <Navbar />
    <!-- End Header -->

    <!-- ======= Hero Section ======= -->
    <HeroSection />
    <!-- End Hero -->

    <main id="main">
      <!-- ======= About Section ======= -->
      <About />
      <!-- ======= About Section ======= -->

      <!-- ======= Counts Section ======= -->
      <CountsData />
      <!-- End Counts Section -->

      <!-- ======= Catalog Section ======= -->
      <Catalog />
      <!-- End Catalog Section -->

    </main>
    <!-- End #main -->

    <!-- ======= Footer ======= -->
    <Footer />
    <!-- End Footer -->

    <a
      href="#"
      class="back-to-top d-flex align-items-center justify-content-center"
      ><i class="bi bi-arrow-up-short"></i
    ></a>
  </div>
</template>

<script>
import Navbar from '~/components/Navbar.vue'
import HeroSection from '~/components/HeroSection.vue'
import About from '~/components/About.vue'
import CountsData from '~/components/CountsData.vue'
import Catalog from '~/components/Catalog.vue'
import Footer from '~/components/Footer.vue'
export default {
  name: 'IndexPage',
  components: {
    Navbar,
    HeroSection,
    About,
    CountsData,
    Catalog,
    Footer,
  },
}
</script>
