<template>
  <div>
    <button @click="start()">
      <i class="glyphicon glyphicon-play"></i>
    </button>
    <button :disabled="state!=='started'" @click="pause()">
      <i class="glyphicon glyphicon-pause"></i>
    </button>
    <button :disabled="state!=='started' && state !== 'paused'" @click="stop()">
      <i class="glyphicon glyphicon-stop"></i>
    </button>
  </div>
</template>

<style scoped>
</style>

<script>
</script>
