<template>
  <section id="app">
    <h1>Counter</h1>
    <CompositionAPIComponent></CompositionAPIComponent>
    <OptionsAPIComponent></OptionsAPIComponent>
  </section>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import CompositionAPIComponent from './components/CompositionAPIComponent.vue'
import OptionsAPIComponent from './components/OptionsAPIComponent.vue'

export default defineComponent({
  name: 'App',
  components: {
    CompositionAPIComponent,
    OptionsAPIComponent,
  },
})
</script>

<style>
#app {
  font-family: Arial, sans-serif;
}
</style>
