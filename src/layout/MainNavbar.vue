<template>
  <navbar
    position="fixed"
    type="primary"
    :transparent="transparent"
    :color-on-scroll="colorOnScroll"
    menu-classes="ml-auto"
  >
    <template>
      <router-link class="navbar-brand" to="/">
        <img
          class="n-logo"
          src="@/assets/Png masterpart-2240x560.png"
          alt=""
          width="112px"
        />
      </router-link>
    </template>
    <template slot="navbar-menu">
      <li class="nav-item">
        <router-link tag="a" class="nav-link" to="/">
          <i class="now-ui-icons tech_tv"></i>
          &nbsp;
          <p>Home</p>
        </router-link>
      </li>
      <li class="nav-item">
        <router-link tag="a" class="nav-link" to="/profile">
          <i class="now-ui-icons users_single-02"></i>
          &nbsp;
          <p>About me</p>
        </router-link>
      </li>
      <li class="nav-item">
        <router-link tag="a" class="nav-link" to="/landing">
          <i class="now-ui-icons files_single-copy-04"></i>
          &nbsp;
          <p>Projects</p>
        </router-link>
      </li>
      <!--<li class="nav-item">
        <a
          class="nav-link btn btn-neutral"
          href="https://www.creative-tim.com/product/vue-now-ui-kit-pro"
          target="_blank"
        >
          <i class="now-ui-icons arrows-1_share-66"></i>
          <p>Upgrade to PRO</p>
        </a>
      </li>-->
      <li class="nav-item">
        <a
          class="nav-link"
          rel="tooltip"
          title="Our Facebook"
          data-placement="bottom"
          href="https://www.facebook.com/masterpartstudios"
          target="_blank"
        >
          <i class="fab fa-facebook-f"></i>
          <p class="d-lg-none d-xl-none">Facebook</p>
        </a>
      </li>
      <li class="nav-item">
        <a
          class="nav-link"
          rel="tooltip"
          title="My LinkedIn"
          data-placement="bottom"
          href="https://www.linkedin.com/in/ivanmota09/"
          target="_blank"
        >
          <i class="fab fa-linkedin-in"></i>
          <p class="d-lg-none d-xl-none">LinkedIn</p>
        </a>
      </li>
      <li class="nav-item">
        <a
          class="nav-link"
          rel="tooltip"
          title="My Github"
          data-placement="bottom"
          href="https://github.com/VmasterpartV"
          target="_blank"
        >
          <i class="fab fa-github"></i>
          <p class="d-lg-none d-xl-none">Github</p>
        </a>
      </li>
    </template>
  </navbar>
</template>

<script>
import { DropDown, Navbar, NavLink } from '@/components'
import { Popover } from 'element-ui'
export default {
  name: 'main-navbar',
  props: {
    transparent: Boolean,
    colorOnScroll: Number
  },
  components: {
    DropDown,
    Navbar,
    NavLink,
    [Popover.name]: Popover
  }
}
</script>

<style scoped></style>
