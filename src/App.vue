<template>
  <div id="app">
    <navigat> </navigat>
    <router-view/>
  </div>
</template>

<script>
import Navigat from './components/Navigation.vue'

export default {
  name: 'App',
  components: {
    Navigat
  }
}
</script>

<style>

</style>
