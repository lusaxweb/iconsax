<template>
    <div class="slide">
        <div class="text">
            <div class="title">
                Hello welcome to icon<b>sax</b>  <br> the oficial icons if the <br> <b>Vuesax</b>  framework
            </div>
            <div class="btns">
                <a download href="/Iconsax.zip">Download</a>
                <button>
                    Download all v1.0
                </button>
                <button class="gray">
                    See vuesax framework
                </button>
            </div>
        </div>
        <div class="icons">
            <div class="con-icons1">
                
            </div>
            <div class="con-icons2">

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
.slide
    background: -color('color')
    display: flex
    padding-bottom: 100px
    align-items: center
    justify-content: center
    padding-top: 50px
    .icons
        width: 50vw
        display: flex
        align-items: center
        justify-content: center
        position: relative
        .con-icons1
            width: 450px
            height: 300px
            background: rgba(255,255,255,1)
            border-radius: 40px 40px 0px 0px
            box-shadow: 0px -20px 60px -15px rgba(0,0,0,.04)
        .con-icons2
            width: 350px
            height: 200px
            background: rgba(255,255,255,1)
            position: absolute
            border-radius: 40px 40px 0px 0px
            transform: translate(-200px, 120px)
            box-shadow: 0px -20px 60px -15px rgba(0,0,0,.04)
    .text
        width: 50vw
        max-width: 650px
        .title
            font-size: 50px
            
            font-weight: 100
            padding-left: 35px
            padding-bottom: 10px
.btns
    margin: 0px 30px
    button
        padding: 14px 24px
        background: rgba(23, 82, 254, 1)
        border: 0px
        border-radius: 16px
        color: rgba(255, 255, 255, 1)
        margin: 10px 5px
        &:not(.gray)
            box-shadow: 0px 10px 25px 0px rgba(23, 82, 254, .2)
        &.gray
            background: rgba(244, 247, 250, 1)
            color: rgba(0,0,0,1)
</style>