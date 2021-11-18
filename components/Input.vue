<template>
<div class="flex justify-center flex-col items-center mb-5">
    <input class="input" type="tel" id="phone" name="phone" placeholder="Phone number" required>

</div>
</template>

<style>

    .input{
        border: none;
        min-width: 300px;
        width: 100%;
        height: 48px;
        border-radius: 24px;
        font-family: Arial, sans-serif;
        font-weight: 400;
        font-size: 20px;
        outline: none;
        /* color:#424242; */
        padding: 12px 26px;
        background-color: #ffffff;
        box-shadow: 2px 2px 2px 2px rgba(#00EE33);
    }
    .input:focus{
        box-shadow: 0px 0px 12px -1px rgba(0,238,51,1);
        -webkit-box-shadow: 0px 0px 12px -1px rgba(0,238,51,1);
        -moz-box-shadow: 0px 1px 12px -13px rgba(0,238,51,1);
    }
    input:required:invalid {
        border-color: #C00000;
    }
</style>