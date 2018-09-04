<template>
  <div class="navbar-container">
      <p>Navbar</p>
      <span class="spacer"></span>
      <a class="social_link" href="" target="_blank"><i class="fab fa-instagram"></i></a>
  </div>
</template>

<script>

export default {
  name: 'AppNavbar'
}
</script>

<style lang="scss" scoped>
    .navbar-container {
        display: flex;
    }
    .social_link {
        color: white;
        font-size: 24px;
    }
</style>
