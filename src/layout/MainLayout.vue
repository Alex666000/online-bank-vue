<template>
  <div class="container with-nav">
    <the-navbar></the-navbar>
    <router-view/>
  </div>
</template>



<script>
import TheNavbar from '@/components/TheNavbar'

export default {
  components: { TheNavbar }

}
</script>



<style scoped>

</style>
