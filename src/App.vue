<template>
  <div id="app">
    <AppNavbar class="nav" />
    <AppMainSection class="main" />
    <AppFooter class="foot" />
  </div>
</template>

<script>
import AppNavbar from './components/AppNavbar'
import AppMainSection from './components/AppMainSection'
import AppFooter from './components/AppFooter'

export default {
  name: 'app',
  components: {
    AppNavbar,
    AppMainSection,
    AppFooter
  }
}
</script>

<style lang="scss">

  #app {
    font-family: 'Raleway', sans-serif;
  }

  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  .spacer {
  flex: 1 1 auto;
  }

  .full-width {
    width: 100%;
  }

  .nav {
    width: 100%;
    height: 64px;
    padding: 10px 30px;
    color: white;
    position: fixed;
    top: 0;
  }

  .foot {
    width: 100px;
    height: 128px;
  }

  .main {
    height: 100vh;
    background-color: blue;
    background: url('./assets/images/main.jpeg') center center / cover no-repeat;
  }

</style>
