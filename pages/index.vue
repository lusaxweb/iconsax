<template>
  <div class="landing">
    <Navbar  />
    <div class="center">
      <Slide />
      <Download />
    </div>
    <Mil />
    <Icon-grid/>
    <Icons />
    <License/>
    <Favorite/>
    <FooterIcons/>
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
    width: 100%
    overflow: hidden
    
</style>
