<template>
  <Tringle msg=""/>
  <ButtonInput msg=""/>
  <div v-if="step === 'step-1'"></div>
</template>

<script>
import Tringle from './components/Tringle.vue'
import ButtonInput from './components/ButtonInput.vue'

export default {
  name: 'App',
  components: {
    Tringle,
    ButtonInput
  },
  data () {
    return {
      step: 'step-1'
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
