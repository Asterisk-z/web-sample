<template>
    <!-- ======= Footer ======= -->
  <footer id="footer">

    <div class="footer-newsletter">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-lg-6">
            <h4>Join Our Newsletter</h4>
            <p>Sign up today for free and be the first to get notified on new updates.</p>
            <form @submit="handleNewsletter">
              <input type="email" name="email" v-model="email"><input type="submit" value="Subscribe">
            </form>
          </div>
        </div>
      </div>
    </div>

    <div class="footer-top">
      <div class="container">
        <div class="row">

          <div class="col-lg-3 col-md-6 footer-contact">
            <h3>Ninestars</h3>
            <p>
              SCO 145 <br>
              Deva Ji VIP Plazar Zirakpur<br>
              Mohali india <br><br>
              <strong>Phone:</strong> +9 180 9152 6192<br>
              <strong>Email:</strong> info@akshiptikainfotech.com <br>
            </p>
          </div>

          <div class="col-lg-3 col-md-6 footer-links">
            <h4>Useful Links</h4>
            <ul>
              <li><i class="bx bx-chevron-right"></i> <a href="#">Home</a></li>
              <li><i class="bx bx-chevron-right"></i> <a href="#">About us</a></li>
              <li><i class="bx bx-chevron-right"></i> <a href="#">Services</a></li>
              <li><i class="bx bx-chevron-right"></i> <a href="#">Terms of service</a></li>
              <li><i class="bx bx-chevron-right"></i> <a href="#">Privacy policy</a></li>
            </ul>
          </div>

          <div class="col-lg-3 col-md-6 footer-links">
            <h4>Our Services</h4>
            <ul>
              <li><i class="bx bx-chevron-right"></i> <a href="#">Web Design</a></li>
              <li><i class="bx bx-chevron-right"></i> <a href="#">Web Development</a></li>
              <li><i class="bx bx-chevron-right"></i> <a href="#">Product Management</a></li>
              <li><i class="bx bx-chevron-right"></i> <a href="#">Marketing</a></li>
              <li><i class="bx bx-chevron-right"></i> <a href="#">Graphic Design</a></li>
            </ul>
          </div>

          <div class="col-lg-3 col-md-6 footer-links">
            <h4>Our Social Networks</h4>
            <p>Follow us on all our social media platforms to stay updated.</p>
            <div class="social-links mt-3">
              <a href="https://twitter.com/AkshiptikaI" target="_blank" class="twitter"><i class="bx bxl-twitter"></i></a>
              <a href="https://www.facebook.com/akshiptikainfotech" target="_blank" class="facebook"><i class="bx bxl-facebook"></i></a>
              <a href="https://www.instagram.com/akshiptikainfotech/" target="_blank" class="instagram"><i class="bx bxl-instagram"></i></a>
              <a href="https://www.linkedin.com/company/77111635/admin/recommend/" target="_blank" class="google-plus"><i class="bx bxl-linkedin"></i></a>
              <a href="https://www.akshiptikainfotech.com#6689" target="_blank" class="linkedin"><i class="bx bxl-discord"></i></a>
            </div>
          </div>

        </div>
      </div>
    </div>

    <div class="container py-4">
      <div class="copyright">
        &copy; Copyright <strong><span>Akshiptika</span></strong>. All Rights Reserved
      </div>
    </div>
  </footer><!-- End Footer -->
</template>

<script>
export default {
  name: 'Footer',
  data(){
    return {
      email: ''
    }
  },
  methods: {
    handleNewsletter(e){
      e.preventDefault();
      let email = this.email
      console.log(email)
      this.email = ''
    }
  }
}
</script>

<style scoped>

</style>