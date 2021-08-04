<template>
    <div  class="download">
        <div class="title">
            <img src="/down1.svg" alt=""> Download in your favorite format
        </div>
        <div v-dragscroll.x="!touchDevice" class="con-cards">
            <a download="iconsax-figma.zip" href="/Iconsax/Figma.zip" class="card">
                <img src="/logos_herramientas/iconsax-figma.svg" alt="">
                <span>
                    .Fig
                </span>
            </a>
            <a download="iconsax-xd.zip" href="/Iconsax/Xd.zip" class="card">
                <img src="/logos_herramientas/iconsax-adobexd.svg" alt="">
                <span>
                    .Xd
                </span>
            </a>
            <a download="iconsax-sketch.zip" href="/Iconsax/Sketch.zip" class="card">
                <img src="/logos_herramientas/iconsax-sketch.svg" alt="">
                <span>
                    .Sketch
                </span>
            </a>
            <a download="iconsax-css.zip" href="/Iconsax/css.zip" class="card">
                <img src="/logos_herramientas/iconsax-css.svg" width="85px" alt="">
                <span>
                    .CSS
                </span>
            </a>
            <a target="_blank" href="https://pub.dev/packages/iconsax" class="card">
                <img src="/logos_herramientas/iconsax-flutter.svg" width="85px" alt="">
                <span>
                    Flutter
                </span>
            </a>
            <a download="iconsax-svg.zip" href="/Iconsax/Svg.zip" class="card">
                <img src="/logos_herramientas/iconsax-svg.svg" width="90px" alt="">
                <span>
                    .SVG
                </span>
            </a>
            
            <a download="iconsax-ai.zip" href="/Iconsax/AI.zip" class="card">
                <img src="/logos_herramientas/iconsax-ai.svg"  alt="">
                <span>
                    .AI
                </span>
            </a>
            <a download="iconsax-jar.zip" href="/Iconsax/Jar.zip" class="card">
                <img src="/logos_herramientas/iconsax-jar.svg"  alt="">
                <span>
                    .Jar
                </span>
            </a>
            
            <div class="space"></div>
        </div>
    </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
    data () {
        return {
            touchDevice: false
        }
    },
    
    mounted() {
        this.touchDevice = ('ontouchstart' in window || navigator.msMaxTouchPoints) || false as any
        console.log(('ontouchstart' in window || navigator.msMaxTouchPoints) || false)
    }
})
</script>

<style lang="sass" scoped>
.download
    max-width: 1800px
    margin: auto
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
    transition: all .25s ease
    color: rgba(0,0,0,1)
    cursor: pointer
    &:hover
        background: rgba(255,255,255,0)
        box-shadow: 0px 20px 100px 0px rgba(0,0,0,.0)
        transform: scale(0.95)
        img
            transform: scale(1.2)
    img
        transition: all .25s ease 
    >span
        position: absolute
        bottom: 25px
        right: 25px
        font-size: 20px
    
</style>