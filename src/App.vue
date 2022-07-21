<template>
  <div id="app">
    <Title/>
    <Jumbotron/>
  </div>
</template>

<script>
import Title from './components/Title.vue'
import Jumbotron from './components/Hero.vue'

export default {
  name: 'App',
  components: {
    Title,
    Jumbotron,
}
}
</script>
<style>
  body {
    text-align: center;
    background-color: darkslateblue;
  }
</style>
