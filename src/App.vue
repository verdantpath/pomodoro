<template>
  <div id="app" class="container">
    <h2>
      <span>Pomodoro</span>
      <controls-component></controls-component>
    </h2>
    <state-title-component></state-title-component>
    <countdown-component></countdown-component>
    <kittens-component></kittens-component>
  </div>
</template>

<script>
import ControlsComponent from './components/ControlsComponent.vue'
import CountdownComponent from './components/CountdownComponent.vue'
import KittensComponent from './components/KittensComponent.vue'
import StateTitleComponent from './components/StateTitleComponent.vue'

export default {
  components: {
    ControlsComponent,
    CountdownComponent,
    KittensComponent,
    StateTitleComponent
  }
}
</script>

<style>
</style>
