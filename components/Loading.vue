<template>
        <div v-if="loading" class="loading-page">
            <p>Loading...</p>
        </div>
</template>

<script>
export default {
  mounted() {
    this.$nextTick(() => {
      this.$nuxt.$loading.start()
      setTimeout(() => this.$nuxt.$loading.finish(), 5000)
    })
  },
  data: () => ({
      loading: false
    }),
    methods: {
      start() {
        this.loading = true
      },
      finish() {
        this.loading = false
      }
    }
}
</script>

<style scoped>
  .loading-page {
    width: 400px;
    height: 20px;
    background: rgba(255, 255, 255, 0.8);
    color: red;
    text-align: center;
    font-size: 30px;
    font-family: sans-serif;
    position: fixed; 
    top: 50%; 
    left: 50%; 
    transform: translate(-50%, -50%);
    /* position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(255, 255, 255, 0.8);
    text-align: center;
    padding-top: 200px;
    font-size: 30px;
    font-family: sans-serif;
    color:red; */
  }
</style>