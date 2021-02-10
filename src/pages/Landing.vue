<template>
  <div>
    <div class="page-header page-header-small">
      <parallax
        class="page-header-image"
        style="background-image: url('img/pexels-2.jpg')"
      >
      </parallax>
      <div class="content-center">
        <div class="container">
          <div class="content-center brand">
            <img class="n-logo" src="@/assets/LogoMG_blanco_s-f.png" alt="" />
            <h1 class="h1-seo">
              Masterpart Studios
            </h1>
          </div>
          <br />
          <br />
          <br />
        </div>
      </div>
    </div>
    <div class="section section-about-us">
      <div class="container">
        <div class="row">
          <div class="col-md-8 ml-auto mr-auto text-center">
            <h2 class="title">Who we are?</h2>
            <h5 class="description">
              We are a software development company that is currently venturing
              into custom web page development, digital design and video game
              development.
            </h5>
          </div>
        </div>
        <div class="separator separator-primary"></div>
        <div class="section-story-overview">
          <div class="row">
            <div class="col-md-6">
              <div
                class="image-container image-left"
                style="background-image: url('img/log.png')"
              >
                <!-- First image on the left side -->
                <p class="blockquote blockquote-primary">
                  We are dedicated to making "Creations of the mind to reality.
                  One line at a time."
                  <br />
                  <br />
                  <small>-Our company</small>
                </p>
              </div>
              <!-- Second image on the left side of the article -->
              <div
                class="image-container"
                style="background-image: url('img/log-3.png')"
              ></div>
            </div>
            <div class="col-md-5">
              <!-- First image on the right side, above the article -->
              <div
                class="image-container image-right"
                style="background-image: url('img/log-2.png')"
              ></div>
              <h3>
                So what does the new record for the lowest level of winter ice
                actually mean
              </h3>
              <p>
                Currently the presence on the internet has become of utmost
                importance for companies of all types and sizes, its integration
                with different software, greatly facilitates work, gives a good
                image and inspires absolute professionalism, at Masterpart
                Studios we are fully committed to deliver high quality products,
                both visual and functional, for us we take each project as ours
                and we work on it in the same way. We are highly convinced that
                each job will provide us with experience and therefore we
                correspond with a useful contribution to your company.
              </p>
              <p>
                In addition to the above, we make unique and important designs,
                whether to give life to your website, or to impact your clients
                on their social networks, we are committed to providing a
                feedback service and working together with you to reach the
                desired result.
              </p>
              <p>
                As for video games, we are currently venturing into it, at the
                moment we do not develop video games for third parties in the
                future we would like to do so, meanwhile you can enjoy our
                creations for your entertainment and thinking of new ideas.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="section section-team text-center">
      <div class="container">
        <h2 class="title">Our team</h2>
        <div class="team">
          <div class="row">
            <div class="col-md-4"></div>
            <div class="col-md-4">
              <div class="team-player">
                <img
                  src="img/yo.jpg"
                  alt="Thumbnail Image"
                  class="rounded-circle img-fluid img-raised"
                />
                <router-link to="/ivanmota">
                  <h4 class="title">Iván Mota</h4>
                </router-link>
                <p class="category text-primary">
                  Software Engineering Student
                  <br />
                  Photographer
                  <br />
                  Freelancer designer
                </p>
                <p class="description">
                  I'm passionate about programming with an insatiable desire to
                  learn, actually I'm study computational systems engineering at
                  the
                  <a href="https://www.itmerida.mx/" target="_blank"
                    >Tecnological Institute of Merida</a
                  >
                  in Yucatan, Mexico and works how a freelancer designer,
                  photographer and software developer.
                </p>
                <a
                  href="https://www.facebook.com/profile.php?id=100005356991809"
                  target="_blank"
                  class="btn btn-primary btn-icon btn-round"
                  ><i class="fab fa-facebook-f"></i
                ></a>
                <a
                  href="https://www.instagram.com/ivanmota_/"
                  target="_blank"
                  class="btn btn-primary btn-icon btn-round"
                  ><i class="fab fa-instagram"></i
                ></a>
                <a
                  href="https://www.linkedin.com/in/ivanmota09/"
                  target="_blank"
                  class="btn btn-primary btn-icon btn-round"
                  ><i class="fab fa-linkedin-in"></i
                ></a>
                <a
                  href="https://github.com/VmasterpartV"
                  target="_blank"
                  class="btn btn-primary btn-icon btn-round"
                  ><i class="fab fa-github"></i
                ></a>
              </div>
            </div>
            <div class="col-md-4"></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import { Button, FormGroupInput } from '@/components'
export default {
  name: 'landing',
  bodyClass: 'landing-page',
  components: {
    [Button.name]: Button,
    [FormGroupInput.name]: FormGroupInput
  },
  data () {
    return {
      form: {
        firstName: '',
        email: '',
        message: ''
      }
    }
  }
}
</script>
<style></style>
