<template>
    <div data-aos="fade-up" data-aos-offset="500" data-aos-easing="ease-out-cubic" class="mil">
        <div class="con-mil">
            <!-- <img src="/1000.svg" alt=""> -->
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 954.63 325.67"><defs></defs><g id="Layer_2" data-name="Layer 2"><g id="Layer_1-2" data-name="Layer 1"><g class="cls-1"><path class="cls-2" d="M70.57,6.31h53.06v265.3H63V70.36L16,83.24,1.22,31.32Z"/><path class="cls-2" d="M243,212.86,212.7,324.67H167.22l15.16-111.81Z"/><path class="cls-2" d="M447.49,239.2q-28.62,37.73-79.4,37.71t-79.4-37.71Q260.07,201.49,260.07,139T288.69,38.71Q317.29,1,368.09,1t79.4,37.71Q476.1,76.44,476.1,139T447.49,239.2ZM320.71,139q0,78.82,47.38,78.83T415.46,139q0-78.83-47.37-78.84T320.71,139Z"/><path class="cls-2" d="M686.25,239.2q-28.62,37.73-79.4,37.71t-79.4-37.71Q498.83,201.49,498.84,139T527.45,38.71Q556.07,1,606.85,1t79.4,37.71Q714.87,76.44,714.87,139T686.25,239.2ZM559.48,139q0,78.82,47.37,78.83T654.23,139q0-78.83-47.38-78.84T559.48,139Z"/><path class="cls-2" d="M925,239.2q-28.62,37.73-79.4,37.71t-79.4-37.71Q737.6,201.49,737.6,139T766.22,38.71Q794.83,1,845.62,1T925,38.71Q953.63,76.44,953.63,139T925,239.2ZM798.24,139q0,78.82,47.38,78.83T893,139q0-78.83-47.37-78.84T798.24,139Z"/></g></g></g></svg>
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
<style scoped>

</style>
<style lang="sass">
.cls-1
    isolation: isolate
.cls-2
    fill: #fff
    stroke: #ebebef
    stroke-width: 2px
    transition: all .25s ease
.mil
    display: flex
    align-items: center
    justify-content: center
    padding: 100px 50px
    &:hover
        .cls-2
            fill: #ebebef
    .number
        font-size: 20rem
        font-weight: bold
        color: #fff
        text-shadow: 0 0 5px #000
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