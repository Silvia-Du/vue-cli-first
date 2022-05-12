<template>
  <div>
    <HeaderNew />
  </div>
</template>

<script>

import HeaderNew from './components/HeaderNew.vue';


export default {
  name: 'App',
  components: {
    HeaderNew
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


  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

</style>
