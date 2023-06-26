< >
  <div>
    <nuxt />
  </div>
</ >


<script>

  export default {
    components: {
    },
    head(){
      return {
        title: "Indutri - Vue Nuxt Industry & Factory Business  "
      }
    },
    mounted(){
      this.$nextTick(() => {
        this.$nuxt.$loading.start()
        setTimeout(() => this.$nuxt.$loading.finish(), 500)
      })
    }
  }
</script>

<style>
</style>
