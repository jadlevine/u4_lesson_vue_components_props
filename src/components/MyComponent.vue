<template>
  <div>
    <!-- render msg here -->
    <h3>{{ msg }}</h3>
  </div>
</template>

<script>
  export default {
    name: 'MyComponent',
    props: {
      msg: {
        type: String,
        required: true 
      }
      // props: ['msg'] //=> can declare props as array of strings too
    }
  }
</script>

<!-- optional -->
<style>
  h3 {
    color: #80CBC4
  }
</style>