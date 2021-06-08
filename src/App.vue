<template>
  <div id="app">
    <the-header></the-header>
    <the-navbar></the-navbar>
    <router-view></router-view>
    <the-footer></the-footer>
  </div>
</template>

<script>
import Header from './components/Header'
import Footer from './components/Footer'
import Navbar from './components/Navbar'

export default {
  name: 'App',
  components: {
  'the-header': Header,
  'the-footer': Footer,
  'the-navbar': Navbar
  }
}
</script>

<style scoped>
#app {
 background: linear-gradient(rgba(0,0,0,0), rgba(0,0,0,.8)), url('~@/assets/backgroud.jpg') no-repeat;
 background-size: cover;
 background-position: center
 ;
 height: 100%;
 width: 100%;
}
</style>
