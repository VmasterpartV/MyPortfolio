<template>
  <nav class="navbar topNav" role="navigation" aria-label="main navigation">
    <div class="navbar-brand">
      <router-link class="navbar-item" tag="a" to="/">
        <img
          src="@/assets/logo.png"
          alt="Bulma: Free, open source, and modern CSS framework based on Flexbox"
          width="112"
          height="28"
        />
      </router-link>

      <a
        role="button"
        class="navbar-burger"
        aria-label="menu"
        aria-expanded="false"
      >
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
      </a>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'NavBar'
}
</script>

<style scoped>
.navbar {
  z-index: 2;
  position: fixed;
  left: 0;
  top: 0;
  z-index: 2;
  background-color: white;
  justify-content: space-around;
  width: 100%;
  border-bottom: 1px solid lightgray;
}

.topNav {
  border-top: 5px solid #206bc2;
}
</style>
