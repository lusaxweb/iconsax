<template>
    <div data-aos="fade-up"  data-aos-offset="500" class="Favorite">
        <div class="con-Favorite">
            <h2>
                In your favorite formats
            </h2>
            <div class="con-animate">
                <h1>
                    icon<b>sax</b>
                </h1>
                <div class="circle1"></div>
                <div class="circle2"></div>


                <div class="image1 image">
                    <img src="/logos_herramientas/iconsax-figma.svg" alt="">
                </div>
                <div class="image2 image">
                    <img src="/logos_herramientas/iconsax-adobexd.svg" alt="">
                </div>
                <div class="image3 image">
                    <img src="/logos_herramientas/iconsax-sketch.svg" alt="">
                </div>
                <div class="image4 image">
                    <img src="/logos_herramientas/iconsax-svg.svg" width="80px" alt="">
                </div>
                <div class="image5 image">
                    <img src="/logos_herramientas/iconsax-jar.svg" alt="">
                </div>
                <div class="image6 image">
                    <img src="/logos_herramientas/iconsax-ai.svg" alt="">
                </div>
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
.Favorite
    display: flex
    align-items: center
    justify-content: center
    padding: 100px 0px
    h1
        font-size: 38px
        z-index: 100
        position: relative
    h2
        text-align: center
        font-size: 35px
        font-family: 'Gilroy'
        padding: 20px

@keyframes scale
    0%
        transform: scale(1)
    16.5%
        transform: scale(1.25)
    33%
        transform: scale(1)
    100%
        transform: scale(1)

@keyframes expand
    0%
        transform: scale(1)
        box-shadow: 0px 0px 30px 0px rgba(0,0,0,.0)
    33%
        transform: scale(1.4)
        box-shadow: 0px 0px 30px 0px rgba(0,0,0,.05)
    66%
        transform: scale(1.8)
        box-shadow: 0px 0px 100px 0px rgba(0,0,0,.0)
    100%
        transform: scale(1)
        box-shadow: 0px 0px 100px 0px rgba(0,0,0,.0)
.con-Favorite
    display: flex
    align-items: center
    justify-content: center
    flex-direction: column
.con-animate
    width: 500px
    height: 500px
    display: flex
    align-items: center
    justify-content: center
    border: 2px dashed rgba(0,0,0,.06)
    border-radius: 50%
    position: relative
    margin-top: 80px
    .circle1
        width: 260px
        height: 260px
        background: #fff
        border-radius: 50%
        box-shadow: 0px 0px 30px 0px rgba(0,0,0,.05)
        position: absolute
        z-index: -1
        animation: expand 3s ease infinite
    .circle2
        width: 320px
        height: 320px
        background: #fff
        border-radius: 50%
        box-shadow: 0px 0px 30px 0px rgba(0,0,0,.05)
        position: absolute
        z-index: -2
        animation: expand 3s linear infinite
    .image
        position: absolute
        &.image1
            left: 0px
            top: 100px
            animation: scale 15s ease infinite
        &.image2
            top: -40px
            animation: scale 15s ease infinite 2.5s
        &.image3
            right: 0px
            top: 100px
            animation: scale 15s ease infinite 5s
        &.image4
            bottom: 100px
            right: 0px
            animation: scale 15s ease infinite 7.5s
        &.image5
            bottom: -40px
            animation: scale 15s ease infinite 10s
        &.image6
            bottom: 100px
            left: 0px
            animation: scale 15s ease infinite 12.5s
@media (max-width: 640px)
    .con-animate
        width: 400px
        height: 400px
        .image
            &.image1
                left: 0px
                top: 80px
            &.image2
                top: -40px
            &.image3
                right: 0px
                top: 80px
            &.image4
                bottom: 80px
                right: 0px
            &.image5
                bottom: -40px
            &.image6
                bottom: 80px
                left: 0px
@media (max-width: 460px)
    .con-animate
        width: 300px
        height: 300px
        margin-top: 30px
        .image
            img
                width: 50px
            &.image1
                left: 0px
                top: 50px
            &.image2
                top: -20px
            &.image3
                right: 0px
                top: 50px
            &.image4
                bottom: 50px
                right: 0px
            &.image5
                bottom: -30px
            &.image6
                bottom: 35px
                left: 0px

</style>