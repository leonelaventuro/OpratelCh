<template>
<div class="flex justify-center flex-col items-center">
    <button class="button">{{btnText}}</button>
</div>
</template>

<script>
export default {
    props: ['btnText']
}
</script>

<style>
    .button{
        background-color: #02bc2a;
        min-width: 300px;
        width: 100%;
        height: 48px;
        left: 30px;
        top: 350px;
        border-radius: 24px;
        color: #ffffff;
        text-transform: uppercase;
        font-size: 26px;
        font-family:'Rajdhani',sans-serif;
        line-height: 33,18px;
        font-weight: 700;
        cursor: pointer;
    }
</style>