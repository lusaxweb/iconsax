<template>
    <div class="mil">
        <div class="con-mil">
            <img src="/1000.svg" alt="">
            <span class="title">
                icons
            </span>
            <p>
                6 diferent styles, total 6000 icons
            </p>
        </div>
    </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
    
})
</script>

<style lang="sass">
.mil
    display: flex
    align-items: center
    justify-content: center
    padding: 100px 50px
    .title
        position: absolute
        right: 0px
        bottom: 0px
        font-size: 100px
        font-weight: bold
        font-family: 'Gilroy-bold'
    p
        position: absolute
        right: 0px
        bottom: -25px
        font-size: 32px
    .con-mil
        width: 100%
        max-width: 900px
        position: relative
        
@media (max-width: 700px)
    .mil
        padding: 50px 50px
    .con-mil
        .title
            font-size: 60px
        p
            font-size: 20px

</style>