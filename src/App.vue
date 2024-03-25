<template>
  <TheNavbar />
  <TheHeader />
  <TheSection1 />
  <TheSection2 />
  <TheSection3 />
</template>

<script>
import TheNavbar from './components/TheNavbar.vue'
import TheHeader from './components/TheHeader.vue'
import TheSection1 from './components/TheSection1.vue'
import TheSection2 from './components/TheSection2.vue'
import TheSection3 from './components/TheSection3.vue'

export default {
  name: 'App',
  components: {
    TheSection1, TheHeader, TheNavbar, TheSection2, TheSection3
  },
  data() {
    return {
    }
  }
}
</script>

<style></style>./components/TheSection.vue./components/TheSection1.vue