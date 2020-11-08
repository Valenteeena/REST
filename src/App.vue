<template>
  <div id="app">
    <test/>
  </div>
</template>

<script>
import test from './components/test.vue'

export default {
  name: 'app',
  components: {
    test
  }
}
</script>

<style>
#app {
    position: relative;
    width:90%;
    margin: auto;
}

</style>
