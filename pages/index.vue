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
//     &:after
//       content: ''
//       position: fixed
//       width: 100%
//       height: 100px
//       left: 0px
//       top: 0px
//       background-image: linear-gradient(0deg, rgba(0,0,0,0.0) 0%,rgba(255,255,255,1) 100%)
//     &:before
//       content: ''
//       position: fixed
//       width: 100%
//       height: 100px
//       left: 0px
//       bottom: 0px
//       z-index: 100
//       background-image: linear-gradient(180deg, rgba(0,0,0,0.0) 0%,rgba(255,255,255,1) 100%)

</style>
