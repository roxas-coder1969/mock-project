<template>
  <div id="app">
    <Example />
  </div> 
</template>

<script>
import Example from './views/Example.vue'
export default {
  name: 'App',
  components: {
    Example
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
  line-height: 1.6;
  background: #ffffff;
}
</style>
