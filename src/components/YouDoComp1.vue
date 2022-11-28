<template>
  <div>
    <p>{{ msg }}</p>
  </div>
</template>

<script>
  export default {
    name: 'YouDoComp1',
    props: {
      msg: {
        type: String,
        required: true 
      }
    }
  }
</script>

<style>
  p {
    background-color: blue;
    color:aliceblue;
  }
</style>