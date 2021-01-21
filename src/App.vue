<template>
  <div id="app">
    <!-- <HelloJSX title="CompositionAPI" msg="This is Composition API sample2"> -->
    <HelloWorld title="CompositionAPI" msg="This is Composition API sample">
  </div>
</template>

<script>
// import HelloJSX from './components/HelloJSX.jsx'
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    // HelloJSX,
    HelloWorld
  }
}
</script>
