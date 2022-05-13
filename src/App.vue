<template>
  <div>
    <HeaderNew />
    <MyHero />

  </div>
</template>

<script>

import HeaderNew from './components/HeaderNew.vue';

import MyHero from './components/MyHero.vue';

export default {
  name: 'App',
  components: {
    HeaderNew,
    MyHero,
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
