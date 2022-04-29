<template>
  <footer id="footer">
    <div class="footer-top">
      <div class="container">
        <div class="row">
          <div class="col-lg-3 col-md-6 footer-contact">
            <h3>Catalog</h3>
            <p>
              Online Store <br />
              contact us<br /><br />
              <strong>Phone:</strong> +62 8560 55488 55<br />
              <strong>Email:</strong> catalogonline@gmail.com<br />
            </p>
          </div>

          <div class="col-lg-2 col-md-6 footer-links">
            <h4>Useful Links</h4>
            <ul>
              <li><i class="bx bx-chevron-right"></i> <nuxt-link to="#hero">Home</nuxt-link></li>
              <li>
                <i class="bx bx-chevron-right"></i> <nuxt-link to="#about">About</nuxt-link>
              </li>
              <li><i class="bx bx-chevron-right"></i> <nuxt-link to="#catalog">Catalog</nuxt-link></li>
              <li>
                <i class="bx bx-chevron-right"></i> <nuxt-link to="#footer">Contact</nuxt-link>
              </li>
            </ul>
          </div>

          <div class="col-lg-3 col-md-6 footer-links">
            <h4>Our Social Media</h4>
            <ul>
              <li>
                <i class="bx bx-chevron-right"></i>
                <a href="#">WhatsApp : 0743298379</a>
              </li>
              <li>
                <i class="bx bx-chevron-right"></i>
                <a href="#">Instagram : @catalogonline_</a>
              </li>
              <li>
                <i class="bx bx-chevron-right"></i>
                <a href="#">Facebook : Catalog Online</a>
              </li>
            </ul>
          </div>

          <div class="col-lg-4 col-md-6 footer-newsletter">
            <h4>Join Our Membership</h4>
            <p>
              Tamen quem nulla quae legam multos aute sint culpa legam noster
              magna
            </p>
            <form action="" method="post">
              <input type="email" name="email" /><input
                type="submit"
                value="Join Now"
              />
            </form>
          </div>
        </div>
      </div>
    </div>

    <div class="container d-md-flex py-4">
      <div class="me-md-auto text-center text-md-start">
        <div class="copyright">
          &copy; Copyright <strong><span>ThunderLab</span></strong
          >. All Rights Reserved
        </div>
        <div class="credits">
          <!-- All the links in the footer should remain intact. -->
          <!-- You can delete the links only if you purchased the pro version. -->
          <!-- Licensing information: https://bootstrapmade.com/license/ -->
          <!-- Purchase the pro version with working PHP/AJAX contact form: https://bootstrapmade.com/bethany-free-onepage-bootstrap-theme/ -->
          Designed by <a href="#">Marthanadiva</a>
        </div>
      </div>
      <div class="social-links text-center text-md-right pt-3 pt-md-0">
        <a href="#" class="twitter"><i class="bx bxl-twitter"></i></a>
        <a href="#" class="facebook"><i class="bx bxl-facebook"></i></a>
        <a href="#" class="instagram"><i class="bx bxl-instagram"></i></a>
        <a href="#" class="google-plus"><i class="bx bxl-skype"></i></a>
        <a href="#" class="linkedin"><i class="bx bxl-linkedin"></i></a>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
    name: 'Footer',
}
</script>