<template>
  <div>
    <div class="page-header page-header-small">
      <parallax
        class="page-header-image"
        style="background-image: url('img/pexels-1.jpg')"
      >
      </parallax>
      <div class="content-center">
        <div class="container">
          <h1 class="title">Projects.</h1>
        </div>
      </div>
    </div>
    <div>
      <br />
      <div class="col-md-10 ml-auto mr-auto">
        <div class="row collections">
          <div class="col-md-6">
            <img src="img/log-2.png" alt="" class="img-raised" />
          </div>
          <div class="col-md-6">
            <img src="img/log.png" alt="" class="img-raised" />
          </div>
        </div>
      </div>
      <br />
      <div class="col-md-10 ml-auto mr-auto">
        <div class="row collections">
          <div class="col-md-6">
            <img src="img/log-5.png" alt="" class="img-raised" />
          </div>
          <div class="col-md-6">
            <img src="img/log-6.png" alt="" class="img-raised" />
          </div>
        </div>
      </div>
      <br />
      <div class="col-md-10 ml-auto mr-auto">
        <div class="row collections">
          <div class="col-md-6">
            <img src="img/log-3.png" alt="" class="img-raised" />
          </div>
          <div class="col-md-6">
            <img src="img/log-4.png" alt="" class="img-raised" />
          </div>
        </div>
      </div>
      <br />
      <div class="col-md-10 ml-auto mr-auto">
        <div class="row collections">
          <div class="col-md-6">
            <img src="img/log-7.png" alt="" class="img-raised" />
          </div>
          <!--<div class="col-md-6">
                  </div>-->
        </div>
      </div>
    </div>
    <br />
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
