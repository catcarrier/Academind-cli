<template>
  <div id="app">
    <h1>{{ makeUpper( monkey ) }}</h1>
  </div>
</template>

<script>
export default {
  data() {
    return {
      monkey: "ssssssSS"
    }
  },
  methods: {
    makeUpper: function(value) { return value.toUpperCase()}
  }
  
}
</script>

<style>

</style>
