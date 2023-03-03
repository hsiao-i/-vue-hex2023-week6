<template>
  <FrontnNavbar />
  <router-view />
</template>

<script>
import FrontnNavbar from '../components/FrontnNavbar.vue'
export default {
  components: {
    FrontnNavbar
  }
}
</script>

<style scoped>
</style>
