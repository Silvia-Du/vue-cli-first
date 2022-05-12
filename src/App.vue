<template>
  <div>
    <HeaderNew />
    <myHero />

  </div>
</template>

<script>

import HeaderNew from './components/HeaderNew.vue';
import myHero from './components/myHero.vue';

export default {
  name: 'App',
  components: {
    HeaderNew,
    myHero
  }
}

</script>

<style lang="scss">


  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
  }


</style>
