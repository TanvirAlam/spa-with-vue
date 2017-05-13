<template>
  <div id="app">
    <component></component>
    <component2></component2>
  </div>
</template>

<script>
import Component from './components/Component.vue'
import Component2 from './components/Component2.vue'
export default {
  name: 'app',
  components: { Component, Component2 },
  data () {
    return {

    }
  }
}
</script>

<style>

</style>
