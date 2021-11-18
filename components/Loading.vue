<template>
   <div>
     <div class="loading relative">
       <div class="barEmpty absolute"></div>
       <div class="barColor absolute"><div class="logoxs flex items-center justify-center"><img src="isologo.png" alt="" style="width:20px; weight: 24px" ></div></div>
       
     </div>
   </div>
</template>

<script>

</script>

<style>
  .barEmpty{
    width: 300px;
    height: 20px;
    background-color: rgba(255, 255, 255, 0.8);
    border-radius: 10px;
  }
    .barColor{
    width: 200px;
    height: 20px;
    background-color: #00EE33;
    border-radius: 10px;
  }
  .logoxs{
    width: 40px;
    height: 40px;
    background-color: #00EE33;
    border-radius: 100%;
    position: absolute;
    left:180px;
    top:-10px;
  }

</style>