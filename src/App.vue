<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <!-- use components here -->
    <MyComponent msg="This is My Component!"/>
    <YouDoComp1 msg="I'm Blue, abu-de-abu-da"/>
    <YouDoComp2 msg1="left" msg2="right"/>
  </div>
</template>

<script>
  // import components here
  import MyComponent from './components/MyComponent'
  import YouDoComp1 from './components/YouDoComp1'
  import YouDoComp2 from './components/YouDoComp2'
  export default {
    name: 'App',
    components: {
      //register components here
      MyComponent,
      YouDoComp1,
      YouDoComp2,
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
