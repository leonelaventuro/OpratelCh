<template>
    <div class="w-full">
        <p class="primary-text flex justify-center flex-col items-center">Please put your phone number to start</p>
        <p class="secondary-text flex justify-center flex-col items-center text-center mt-1 mb-7">Put your 9 digit phone number without spaces nor country code (233). Eg: 912345678</p>
        <Input />
        <Button btn-text="Continue" />
        <!-- <Button btn-text="Suscribe" /> -->
        
    </div>
</template>

<script>
export default {
}
</script>

<style>
.primary-text{
    font-size: 16px;
    font-weight: 700;
    color: #FAC900;
    line-height: 20px;
    font-family: Arial,sans-serif;
}
.secondary-text{
    font-size: 14px;
    font-weight: 400;
    color: #ffffff;
    line-height: 18px;
    font-family: Arial,sans-serif;
}
</style>