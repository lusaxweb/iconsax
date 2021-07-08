<template>
    <div data-aos="fade-up" data-aos-offset="0" class="footer-icons">
        <div class="con-footer-icons">
            <h2>
                Soon <b>v2</b>
            </h2>

            <div class="con-cards">
                <div class="card cardx">
                    <div class="icon" v-for="i in 70" :key="i">
                        <img :src="`/icons/a/${i}.svg`" alt="">
                    </div>
                </div>
                <div class="card card2">
                    <div class="icon" v-for="i in 70" :key="i">
                        <img :src="`/icons/a/${i}.svg`" alt="">
                    </div>
                </div>
                <div class="card card3">
                    <div class="icon" v-for="i in 70" :key="i">
                        <img :src="`/icons/a/${i}.svg`" alt="">
                    </div>
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

<style lang="sass" scoped>
.footer-icons
    padding-top: 100px
    padding-bottom: 100px
    display: flex
    align-items: center
    justify-content: center
    h2
        text-align: center
        font-size: 40px
        font-family: 'Gilroy'
        padding-bottom: 30px
        b
            color: rgba(23, 82, 254, 1)
.con-footer-icons
    width: 100%
    position: relative
.con-cards
    position: relative
    width: 100%
    display: flex
    align-items: center
    justify-content: center
    padding-bottom: 100px
.card
    width: 450px
    height: auto
    background: rgba(255,255,255,1)
    border-radius: 40px 40px 0px 0px
    box-shadow: 0px -20px 60px -15px rgba(0,0,0,.04)
    display: flex
    align-items: flex-start
    justify-content: center
    flex-wrap: wrap
    padding: 16px
    &.cardx
        padding-bottom: 50px
    &.card2
        width: 70%
        position: absolute
        top: 90px
        left: 15%
        z-index: -1
    &.card3
        width: 90%
        position: absolute
        top: 220px
        left: 5%
        z-index: -1
    .icon
        width: 50px
        height: 50px
        display: flex
        align-items: center
        justify-content: center

@media (max-width: 950px)
    .card
        &.card2
            width: 100%
            left: 0px
        &.card3
            display: none


</style>