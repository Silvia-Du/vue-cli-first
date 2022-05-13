<template>

  <header>
    <MyTitle />
  </header>

</template>

<script>


import MyTitle from './MyTitle.vue'


export default {
  name: 'HeaderNew',

  components: {
   MyTitle,
  
  }
}
</script>

<style lang="scss">

  header{
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100px;
    color: aliceblue;
    background-color: #001d4c;
  }

</style>