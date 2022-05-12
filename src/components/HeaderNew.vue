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
    myTitle
  }
}
</script>

<style>

  header{
    height: 80px;
    display: flex;
    justify-content: center;
    align-content: center;
    color: aliceblue;
    background-color: rgb(177, 89, 89);
  }

</style>