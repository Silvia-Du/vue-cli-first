<template>
  <div>
    <HeaderNew />
    <MyMain />
    <MyFooter />
  </div>
</template>

<script>

import HeaderNew from './components/HeaderNew.vue';
import MyMain from './components/MyMain.vue';
import MyFooter from './components/MyFooter.vue';

export default {
  name: 'App',
  components: {
    HeaderNew,
    MyMain,
    MyFooter,
  }
}
/*
Descrizione:
Create un nuovo progetto utilizzando Vue CLI: aiutatevi con le slide per ripercorrere i vari passaggi dell’installazione come visti a lezione.
Create e utilizzate un componente Title, il quale contiene un titolo che recita “La mia prima app con Vue CLI!”
Bonus:
Creare un secondo componente Hero, che visualizza un jumbotron.
*/
</script>

<style lang="scss">

</style>
