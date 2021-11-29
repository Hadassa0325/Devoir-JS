<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <DateSelect msg=" Choisis une date"/>
  <HourSelect msg=" Choisis une heure"/>
  <FindTime msg=" Trouver plus de temps"/>
  <TimesLots msg=" Times Lots" />

</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import DateSelect from './components/DateSelect.vue'
import HourSelect from './components/HourSelect.vue'
import FindTime from './components/FindTime.vue'
import TimesLots from './components/TimesLots.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    DateSelect,
    HourSelect,
    FindTime,
    TimesLots,
  }
}
</script>

<style>

</style>
