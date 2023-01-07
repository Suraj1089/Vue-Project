
<template>
  <NavbarComp v-bind:links="['Home', 'About', 'Contact']"/>
  <LoginComp />
  <FooterComp />
</template>

<script>
import NavbarComp from './components/Navbar'
import LoginComp from './components/Login'
import FooterComp from './components/Footer'
export default {
  name: 'App',
  components: {
    NavbarComp,
    LoginComp,
    FooterComp
  }
}
</script>

<style>
</style>