<template>
    <div class="footer">
        <span>
            Copyright © 2021 Vuesax
        </span>
        <div class="icons">
                <a href="https://www.behance.net/ManuelRovira" target="_blank">
                    <img src="/behance.svg" alt="">
                </a>
                <a href="https://dribbble.com/ManuelRovira" target="_blank">
                    <img src="/dribbble.svg" alt="">
                </a>
                <a href="https://github.com/lusaxweb/iconsax" target="_blank">
                    <img src="/github.svg" alt="">
                </a>
                <a href="https://www.instagram.com/iconsax/" target="_blank">
                    <img src="/instagram.svg" alt="">
                </a>
            </div>
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
    align-items: center
    background: -color('color')
    padding: 0px 25px
    padding-bottom: 20px
    font-size: 13px
    z-index: 1000
    span
        opacity: .4
    .icons
        display: flex
        position: absolute
        left: 50%
        transform: translate(-50%)
        a
            width: 40px
            height: 40px
            display: flex
            align-items: center
            justify-content: center
            transition: all .25s ease
            cursor: pointer
            &:hover
                opacity: .4
    a
        color: rgba(0, 0, 0, 1)
@media (max-width: 812px)
    .footer
        padding-bottom: 20px
        .icons
            transform: translate(-50%, -50px)

</style>