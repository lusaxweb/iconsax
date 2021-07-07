<template>
    <div class="navbar">
        <span class="logo">
            icon<b>sax</b> 
        </span>
        <div class="actions">
            <div class="links">
                <a href="#license">
                    License 
                </a>
            </div>

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
        </div>
    </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
    
})
</script>

<style lang="sass">
.navbar
    background: -color('color')
    padding: 10px 20px
    display: flex
    justify-content: space-between
    width: 100vw
    align-items: center
    .logo
        font-size: 20px
    .actions
        display: flex
        justify-content: flex-end
        align-items: center
        .icons
            display: flex
            a
                width: 40px
                height: 40px
                display: flex
                align-items: center
                justify-content: center
                transition: all .25s ease
                &:hover
                    opacity: .4
        .links
            display: flex
            padding-right: 10px
            a
                margin: 0px 15px
                display: block
                opacity: .5
                color: -color('text')
@media (max-width: 540px)
    .navbar .actions .links
        display: none

</style>