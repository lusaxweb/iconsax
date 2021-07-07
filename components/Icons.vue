<template>
    <div data-aos="fade-up"  data-aos-offset="500" class="icons">
        <div class="con-icons">
            <h2>
                <b>6</b> styles diferents
            </h2>
            <div class="icons-content">
                <div class="con-image">
                    <img src="/chat1.svg" alt="">
                    <p>
                        Icons Linear
                    </p>
                </div>
                <div class="con-image">
                    <img src="/chat2.svg" alt="">
                    <p>
                        Icons Bulk
                    </p>
                </div>
                <div class="con-image">
                    <img src="/chat3.svg" alt="">
                    <p>
                        Icons Two Tone
                    </p>
                </div>
                <div class="con-image">
                    <img src="/chat4.svg" alt="">
                    <p>
                        Icons Bold
                    </p>
                </div>
                <div class="con-image">
                    <img src="/chat5.svg" alt="">
                    <p>
                        Icons Outline
                    </p>
                </div>
                <div class="con-image">
                    <img src="/chat6.svg" alt="">
                    <p>
                        Icons Broken
                    </p>
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
.icons
    display: flex
    align-items: center
    justify-content: center
    padding: 100px 50px
    h2
        text-align: center
        font-family: 'Gilroy'
        font-size: 38px
    .icons-content
        display: flex
        max-width: 900px
        flex-wrap: wrap
        align-items: center
        justify-content: center
        .con-image
            margin: 20px
            p
                padding: 10px
                font-size: 17px
                text-align: center
</style>