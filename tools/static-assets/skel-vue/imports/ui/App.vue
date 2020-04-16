<template>
  <div>
    <h1>Welcome to Meteor!</h1>
    <hello/>
    <info/>
  </div>
</template>

<script>
import Hello from './Hello.vue'
import Info from './Info.vue'

export default {
  components: {
    Hello,
    Info,
  },
}
</script>

<style>
  body {
    font-family: sans-serif;
    padding: 10px;
  }
</style>
