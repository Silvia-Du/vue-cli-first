<template>

  <header>
    <myTitle />
  </header>

</template>

<script>

import myTitle from './Title.vue';



export default {
  name: 'HeaderNew',

  components: {
    myTitle,
  
  }
}
</script>

<style>

  header{
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100px;
    color: aliceblue;
    background-color: #001d4c;
  }

</style>