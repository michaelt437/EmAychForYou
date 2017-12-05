<template>
  <div id="app">
    <img src="./assets/mh4u.png">
    <h3>Headgear</h3>
    <ul>
      <li v-for="part in headgear">{{part.name}}</li>
    </ul>
    <h3>Chest</h3>
    <ul>
      <li v-for="part in chest">{{part.name}}</li>
    </ul>
    <h3>Arms</h3>
    <ul>
      <li v-for="part in arms">{{part.name}}</li>
    </ul>
    <h3>Waist</h3>
    <ul>
      <li v-for="part in waist">{{part.name}}</li>
    </ul>
    <h3>Legs</h3>
    <ul>
      <li v-for="part in legs">{{part.name}}</li>
    </ul>
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
      headgear: head_gear,
      chest: chest,
      arms: arms,
      waist: waist,
      legs: legs
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
