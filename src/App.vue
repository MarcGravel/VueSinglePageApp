<template>
  <div id="app">
    <TopHeader></TopHeader>
    <MainBody></MainBody>
    <BottomFoot></BottomFoot>
  </div>
</template>

<script>
import TopHeader from './components/TopHeader.vue'
import MainBody from './components/MainBody.vue'
import BottomFoot from './components/BottomFoot.vue'

export default {
  name: 'App',
  components: {
    TopHeader,
    MainBody,
    BottomFoot
  }
}
</script>

<style>
  * {
    margin: 0;
    padding: 0;
  }

  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
  }
</style>
