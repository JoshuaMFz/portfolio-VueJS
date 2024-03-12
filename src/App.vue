<template>
  <TheNavbar  />
  <TheSection />
  <TheHeader  />
</template>

<script>
  import TheSection from './components/TheSection.vue'
  import TheHeader from './components/TheHeader.vue'
  import TheNavbar from './components/TheNavbar.vue'

  export default {
    name: 'App',
    components: {
      TheSection, TheHeader, TheNavbar
    },
    data() {
      return {
      }
    }
  }
</script>

<style>
</style>./components/TheSection.vue