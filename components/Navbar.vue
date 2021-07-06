<template>
    <div class="navbar">
        <span>
            iconsax
        </span>
        <div class="actions">
            <a href="">
                About
            </a>
            <a href="">
                License
            </a>

            <div class="icons">
                <a href="">
                    Ins
                </a>
                <a href="">
                    Dri
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
    padding: 20px
    display: flex
    justify-content: space-between
    width: 100vw
    .actions
        display: flex
        justify-content: flex-end
        a
            margin: 0px 20px
            color: -color('text')
</style>