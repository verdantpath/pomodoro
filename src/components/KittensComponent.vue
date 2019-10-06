<template>
  <div class="well" :class="{ 'hidden': pomodoroState === 'work' }">
    <img :src="'http://thecatapi.com/api/images/get?type=jpg&size=med&ts=' + timestamp" />
  </div>
</template>

<style scoped>
</style>

<script>
</script>
