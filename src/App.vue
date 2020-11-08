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
    box-shadow: -3px 0px 5px -3px rgba(40,57,75, .5);
  border-top-left-radius: .5rem;
}

</style>
