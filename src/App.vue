<template>
  <div id="app">
    <MyName name="Chiamaka" />
  </div>
</template>

<script>
import MyName from './components/MyName'

export default {
  name: 'App',
  components: {
    MyName
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
  left: 0;
  line-height: 200px;
  margin-top: -100px;
  position: absolute;
  text-align: center;
  top: 50%;
  width: 100%;
}
</style>
