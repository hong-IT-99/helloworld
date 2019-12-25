<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <hello-world msg="Welcome to Your Vue.js App"/>
    <test msg = "Test"/>
    <!-- <test2/> --> 
    <!-- <TestTest msg = "Test"/> -->
  </div>
</template>


<script>
import HelloWorld from './components/HelloWorld'
import test from './components/test'
// import test2 from './components/test'
// import TestTest from './components/test'

export default {
  name: 'app',
  components: {
    HelloWorld,
    test,
    // test2,
    // TestTest
  }
}

</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
