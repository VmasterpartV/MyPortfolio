<template>
  <div>
    <section class="hero is-white is-fullheight">
      <div class="hero-body">
        <div class="container">
          <div class="columns  is-vcentered reverse-columns">
            <div
              class="column
          is-10-mobile is-offset-1-mobile
          is-10-tablet is-offset-1-tablet
          is-5-desktop is-offset-1-desktop
          is-5-widescreen is-offset-1-widescreen
          is-5-fullhd is-offset-1-fullhd"
              data-aos="fade-down"
            >
              <h1 class="title titled is-1 mb-6">
                Hello! I'am Yael Mota, only a engineering student
              </h1>
              <h2
                class=" subtitled subtitle has-text-grey is-4 has-text-weight-normal is-family-sans-serif"
              >
                I am passionate about programming with an insatiable desire to
                learn, actually i'am study computational systems engineering at
                the Tecnological Institute of Merida in Yucatan, Mexico
              </h2>
              <div class="buttons">
                <router-link class="button is-black" tag="a" to="/about">
                  More about me
                </router-link>
              </div>
            </div>
            <div
              data-aos="fade-right"
              class="column
          is-10-mobile is-offset-1-mobile
          is-10-tablet is-offset-1-tablet
          is-4-desktop is-offset-1-desktop
          is-4-widescreen is-offset-1-widescreen
          is-4-fullhd is-offset-1-fullhd"
            >
              <figure class="image is-square">
                <img src="@/assets/undraw_source_code_xx2e.svg" />
              </figure>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="hero is-white is-fullheight">
      <div class="hero-body">
        <div class="container">
          <div class="columns  is-vcentered">
            <div
              data-aos="fade-left"
              class="column
          is-10-mobile is-offset-1-mobile
          is-10-tablet is-offset-1-tablet
          is-4-desktop is-offset-1-desktop
          is-4-widescreen is-offset-1-widescreen
          is-4-fullhd is-offset-1-fullhd"
            >
              <figure class="image is-square">
                <img src="@/assets/definicion-de-persona-min.jpg" />
              </figure>
            </div>
            <div
              data-aos="fade-down"
              class="column
          is-10-mobile is-offset-1-mobile
          is-10-tablet is-offset-1-tablet
          is-5-desktop is-offset-1-desktop
          is-5-widescreen is-offset-1-widescreen
          is-5-fullhd is-offset-1-fullhd"
            >
              <h1 class="titled title is-1 mb-6">
                absurd illustrations that make sense
              </h1>
              <h2 class="subtitled subtitle">
                Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                Laborum cupiditate dolorum vitae dolores nesciunt totam magni
                quas.
              </h2>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="hero is-white is-fullheight">
      <div class="hero-body">
        <div class="container">
          <div class="columns  is-vcentered reverse-columns">
            <div
              data-aos="fade-right"
              class="column
          is-10-mobile is-offset-1-mobile
          is-10-tablet is-offset-1-tablet
          is-5-desktop is-offset-1-desktop
          is-5-widescreen is-offset-1-widescreen
          is-5-fullhd is-offset-1-fullhd"
            >
              <h1 class="title titled is-1 mb-6">
                absurd illustrations that make sense
              </h1>
              <h2 class="subtitle subtitled">
                Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                Laborum cupiditate dolorum vitae dolores nesciunt totam magni
                quas.
              </h2>
            </div>
            <div
              data-aos="fade-up"
              class="column
          is-10-mobile is-offset-1-mobile
          is-10-tablet is-offset-1-tablet
          is-4-desktop is-offset-1-desktop
          is-4-widescreen is-offset-1-widescreen
          is-4-fullhd is-offset-1-fullhd"
            >
              <figure class="image is-square">
                <img src="@/assets/definicion-de-persona-min.jpg" />
              </figure>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="hero is-medium has-text-centered">
      <div class="hero-body">
        <div class="container">
          <div class="columns is-centered">
            <div data-aos="zoom-in-up" class="column is-8">
              <h1 class="title titled is-1 mb-6">
                Primary bold title <span id="typewriter"></span>
              </h1>
              <h2 class="subtitle subtitled">
                Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                Laborum cupiditate dolorum vitae dolores nesciunt totam magni
                quas. Lorem ipsum, dolor sit amet consectetur adipisicing elit.
              </h2>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
// @ is an alias to /src
import AOS from 'aos'

export default {
  name: 'Home',
  mounted () {
    AOS.init()
    new Typewriter('#typewriter', {
      strings: ['typewriter', 'Effect', 'typewriter.js', 'example'],
      autoStart: true,
      loop: true
    })
  }
}
</script>

<style scoped>
@media (max-width: 500px) {
  .reverse-columns {
    flex-direction: column-reverse;
    display: flex;
  }
}

.titled {
  font-family: 'Merriweather', serif !important;
  font-size: 58px !important;
  font-weight: 400 !important;
  line-height: 64px !important;
}

.subtitled {
  font-family: 'Merriweather', serif !important;
  font-size: 22px !important;
  font-weight: 400 !important;
  line-height: 36px !important;
}
</style>
