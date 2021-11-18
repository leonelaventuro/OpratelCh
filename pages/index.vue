<template>
  <div class="flex justify-between flex-col h-screen" style="max-width: 300px;">
      <Header />
      <Content />
      <!-- <Doi /> -->
      <Footer />
  </div>
</template>

<script>
export default {

}
</script>



<style>
body{

    /* font-family: "Rajdhani", sans-serif; */
    position: relative;
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 100%;
    min-height: 100vh;
    background: url(../static/back.png) no-repeat center center fixed;
    background-size: cover;
    margin: 0 auto;
}

</style>

