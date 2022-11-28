<template>
  <div>
    <div class="flex">
      <p class="padded"> {{ msg1 }} </p>
      <p class="padded"> {{ msg2 }} </p>
      </div>
  </div>
</template>

<script>
  export default {
    name: 'YouDoComp2',
    props: ['msg1', 'msg2']
  }
</script>

<style>
  .flex{
    display: flex;
    justify-content: space-between;
    align-content: center;
    height: 30vw;
    width: 70vw;
  }
  .padded {
    padding: 5vw;
  }
</style>