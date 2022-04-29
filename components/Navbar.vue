<template>
  <!-- ======= Header ======= -->
  <header id="header" class="fixed-top d-flex align-items-center">
    <div class="container">
      <div class="header-container d-flex align-items-center justify-content-between">
        <div class="logo">
          <h1 class="text-light"><nuxt-link to="/"><span>Catalog</span></nuxt-link></h1>
        </div>

        <nav id="navbar" class="navbar">
          <ul>
            <li><nuxt-link class="nav-link scrollto active" to="#hero">Home</nuxt-link></li>
            <li><nuxt-link class="nav-link scrollto" to="#about">About</nuxt-link></li>
            <li><nuxt-link class="nav-link scrollto" to="#catalog">Catalog</nuxt-link></li>
            <li><nuxt-link class="nav-link scrollto" to="#footer">Contact</nuxt-link></li>
            <li><nuxt-link class="getstarted scrollto" to="#catalog">Get Started</nuxt-link></li>
          </ul>
          <i class="bi bi-list mobile-nav-toggle"></i>
        </nav><!-- .navbar -->

      </div><!-- End Header Container -->
    </div>
  </header><!-- End Header -->
</template>

<script>
export default {
  name: 'Navbar',
}
</script>
