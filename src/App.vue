<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
import Calc from './components/calc'

export default {
  name: 'App',
  components:{
    Calc
  }
}
</script>

<style>

</style>
