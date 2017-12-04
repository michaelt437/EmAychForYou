<template>
  <div id="app">
    <img src="./assets/mh4u.png">
    <pre>{{chest}}</pre>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import head_gear from './assets/armor/headgear'
import chest from './assets/armor/chest'
import arms from './assets/armor/arms'
import waist from './assets/armor/waist'
import legs from './assets/armor/legs'
export default {
  name: 'app',
  components: {
    HelloWorld
  },
  data() {
    return {
      chest: chest
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
