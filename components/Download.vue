<template>
    <div  class="download">
        <div class="title">
            <img src="/down1.svg" alt=""> Download
        </div>
        <div v-dragscroll class="con-cards">
            <div class="card">
                <span>
                    All the files
                </span>
            </div>
            <div class="card">
                <span>
                    .Figma
                </span>
            </div>
            <div class="card">
                <span>
                    .Xd
                </span>
            </div>
            <div class="card">
                <span>
                    .Sketch
                </span>
            </div>
            <div class="card">
                <span>
                    .SVG
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
    align-items: flex-end
    justify-content: flex-end
    margin: 10px
    padding: 25px
    >span
        font-size: 20px
    
</style>