<template>
    <div  class="download">
        <div class="title">
            <img src="/down1.svg" alt=""> Download
        </div>
        <div v-dragscroll class="con-cards">
            <div class="card">
                <img src="/logos_herramientas/iconsax-figma.svg" alt="">
                <span>
                    .Figma
                </span>
            </div>
            <div class="card">
                <img src="/logos_herramientas/iconsax-adobexd.svg" alt="">
                <span>
                    .Xd
                </span>
            </div>
            <div class="card">
                <img src="/logos_herramientas/iconsax-sketch.svg" alt="">
                <span>
                    .Sketch
                </span>
            </div>
            <div class="card">
                <img src="/logos_herramientas/iconsax-svg.svg" width="90px" alt="">
                <span>
                    .SVG
                </span>
            </div>
            
            <div class="card">
                <img src="/logos_herramientas/iconsax-ai.svg" width="90px" alt="">
                <span>
                    .AI
                </span>
            </div>
            <div class="card">
                <span>
                    .CSS
                </span>
            </div>
            <div class="card">
                <span>
                    .ttf
                </span>
            </div>
            <div class="space"></div>
        </div>
    </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({

})
</script>

<style lang="sass">
.download
    .title
        padding: 0px 40px
        transform: translate(0, 25px)
        font-size: 20px
        display: flex
        align-items: center
        justify-content: flex-start
        img
            margin-right: 10px

.con-cards
    display: flex
    width: 100%
    padding-left: 20px
    padding-top: 40px
    padding-bottom: 40px
    overflow: hidden
.space
    min-width: 40px
    height: 10px
    position: relative
    display: block
.card
    width: 250px
    min-width: 250px
    height: 300px
    background: rgba(255,255,255,1)
    box-shadow: 0px 20px 60px 0px rgba(0,0,0,.03)
    border-radius: 30px
    display: flex
    align-items: center
    justify-content: center
    margin: 10px
    padding: 25px
    position: relative
    >span
        position: absolute
        bottom: 25px
        right: 25px
        font-size: 20px
    
</style>