<template>
    <div class="footer">
        <span>
            Copyright © 2021 Vuesax
        </span>
        <span>
            Created by <a href="https://vuesax.com/">Vuesax</a> 
        </span>
    </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
    
})
</script>

<style lang="sass">
.footer
    display: flex
    justify-content: space-between
    background: -color('color')
    padding: 0px 25px
    padding-bottom: 20px
    opacity: .4
    font-size: 13px
    a
        color: rgba(0, 0, 0, 1)
</style>