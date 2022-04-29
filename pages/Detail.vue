<template>
  <div>
    <!-- ======= Header ======= -->
    <Navbar />
    <!-- End Header -->

    <main id="main">
      <!-- ======= Breadcrumbs ======= -->
      <Breadcrumbs />
      <!-- End Breadcrumbs -->

      <!-- ======= Portfolio Details Section ======= -->
      <section id="portfolio-details" class="portfolio-details">
        <div class="container">
          <div class="row gy-4">
            <div class="col-lg-8">
              <!-- ======= DetailPhoto ======= -->
              <DetailPhoto />
              <!-- End DetailPhoto -->
            </div>

            <div class="col-lg-4">
              <!-- ======= DetailProduct ======= -->
              <DetailProduct />
              <!-- End DetailProduct -->
            </div>
          </div>
        </div>
      </section>
      <!-- End Portfolio Details Section -->
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
import Breadcrumbs from '~/components/Breadcrumbs.vue'
import DetailPhoto from '~/components/DetailPhoto.vue'
import DetailProduct from '~/components/DetailProduct.vue'
import Footer from '~/components/Footer.vue'
export default {
  name: 'DetailPage',
  components: {
    Navbar,
    Breadcrumbs,
    DetailPhoto,
    DetailProduct,
    Footer,
  },
}
</script>
