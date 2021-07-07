<template>
    <div data-aos="fade-up"  data-aos-offset="500" class="icon-grid">
        <div class="con-image">
            <img src="/house-grid.png" alt="">
        </div>
        <div class="con-text">
            <p>
                Perfectly balance, <br> <b>24px</b> grid-based
            </p>
            <a class="download" download href="/Iconsax.zip"><img src="/down2.svg" alt=""> Download all v1.0</a>
        </div>
    </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
    
})
</script>

<style lang="sass">
.icon-grid
    display: flex
    align-items: center
    justify-content: center
    margin-top: 150px
    margin-bottom: 150px
    .con-image
        margin-right: 50px
        img
            max-width: 320px
    .con-text
        margin-left: 50px
        p
            font-size: 40px
            font-family: 'Gilroy'
            padding-bottom: 20px
    a
        padding: 14px 24px
        background: rgba(23, 82, 254, 1)
        border: 0px
        border-radius: 16px
        color: rgba(255, 255, 255, 1)
        margin: 10px 5px
        position: relative
        display: flex
        align-items: center
        justify-content: center
        transition: all .25s ease
        
        img
            margin-right: 10px
        &:not(.gray)
            box-shadow: 0px 10px 25px 0px rgba(23, 82, 254, .2)
            &:hover
                transform: translate(0, 3px)
                box-shadow: 0px 0px 0px 0px rgba(23, 82, 254, 0.2)
        &.gray
            background: rgba(244, 247, 250, 1)
            color: rgba(0,0,0,1)
            &:hover
                background: rgba(239, 242, 245, 1)

@media (max-width: 800px)
    .icon-grid
        flex-direction: column
        align-items: center
        justify-content: center
        .con-image
            margin-right: 0px
            margin-bottom: 30px
            img
                max-width: 250px
        br
            display: none
        .con-text
            margin-top: 20px
            margin-left: 0px
            text-align: center
            padding: 15px
            p
                text-align: center
@media (max-width: 600px)
    .icon-grid
        margin-bottom: 0px
    .icon-grid .con-text p
        font-size: 30px
</style>