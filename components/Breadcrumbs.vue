<template>
    <section id="breadcrumbs" class="breadcrumbs">
      <div class="container">

        <div class="d-flex justify-content-between align-items-center">
          <h2>Product Details</h2>
          <ol>
            <li><nuxt-link to="/">Home</nuxt-link></li>
            <li>Product Details</li>
          </ol>
        </div>

      </div>
    </section>
</template>

<script>
export default {
    name: 'Breadcrumbs',
}
</script>