<template>
  <div class="well">
    <img :src="catImgSrc" />
  </div>
</template>

<style scoped>
.fade-enter-active, .fade-leave-active {
  transition: opacity .5s
}
.fade-enter, .fade-leave-active {
  opacity: 0
}
</style>

<script>
export default {
  computed: {
    catImgSrc () {
      return 'http://thecatapi.com/api/images/get?size=med&ts=' + this.$store.getters.getTimestamp
    }
  }
}
</script>
