<template>
    <div class="slide">
        <div class="text">
            <div class="title">
                Hello welcome to icon<b>sax</b>  <br> the oficial icons if the <br> <b>Vuesax</b>  framework
            </div>
            <div class="btns">
                <a class="download" download href="/Iconsax.zip"><img src="/down2.svg" alt=""> Download all v1.0</a>
                <a href="https://vuesax.com/" target="_blank" class="gray">
                    See vuesax framework
                </a>
            </div>
        </div>
        <div class="icons">
            <div class="con-icons1">
                <div class="icon" v-for="i in 40" :key="i">
                    <img :src="`/icons/${i}a.svg`" alt="">
                </div>
            </div>
            <div class="con-icons2">
                <div class="icon" v-for="i in 24" :key="i">
                    <img :src="`/icons/${i}a.svg`" alt="">
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
.slide
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
            display: flex
            align-items: flex-start
            justify-content: flex-start
            flex-wrap: wrap
            padding: 16px
            .icon
                padding: 14px
        .con-icons2
            width: 350px
            height: 200px
            background: rgba(255,255,255,1)
            position: absolute
            border-radius: 40px 40px 0px 0px
            transform: translate(-200px, 120px)
            box-shadow: 0px -20px 60px -15px rgba(0,0,0,.04)
            display: flex
            align-items: flex-start
            justify-content: flex-start
            flex-wrap: wrap
            padding: 16px
            .icon
                padding: 14px
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
    display: block
    position: relative
    display: flex
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

@media (max-width: 1300px)
    .slide
        .text
            .title
                font-size: 40px
@media (max-width: 1200px)
    .slide
        .icons
            .con-icons2
                transform: translate(0,120px)
@media (max-width: 1050px)
    .slide
        flex-direction: column
        .text
            width: 100vw
            max-width: 100vw
            display: flex
            align-items: center
            justify-content: center
            flex-direction: column
            .btns
                flex: 1
            .title
                flex: 1
                font-size: 35px
                text-align: center
                padding-left: 0px
                br
                    display: none
        .icons
            width: 100vw
            padding-top: 30px
            .con-icons2
                position: relative
                margin-left: 20px
                transform: translate(0,0)
@media (max-width: 570px)
    .slide
        .text
            .title
                padding: 20px
                font-size: 28px
        .icons
            flex-direction: column
            .con-icons1
                align-items: center
                justify-content: center
                width: 100%
            .con-icons2
                display: none
        .btns
            display: flex
            flex-direction: column
            width: 100%
            padding: 0px 30px
            a
                width: 100%
</style>