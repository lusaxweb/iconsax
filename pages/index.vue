<template>
  <div class="landing">
    <Navbar />
    <div class="center">
      <Slide />
      <Download />
    </div>
    <Mil />
    <Icon-grid/>
    <License/>
    <Favorite/>
    <Footer />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({

})
</script>

<style lang="sass">
.landing
    display: flex
    flex-direction: column
    justify-content: space-between
    height: 100vh
    width: 100%
    overflow-x: hidden
</style>
