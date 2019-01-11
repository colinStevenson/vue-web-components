<template>
  <div id="app">
    <ComponentOne />
    <ComponentTwo />
  </div>
</template>

<script>
import ComponentOne from './components/ComponentOne.vue'
import ComponentTwo from './components/ComponentTwo.vue'

export default {
  name: 'app',
  components: {
    ComponentOne,
    ComponentTwo
  }
}
</script>
