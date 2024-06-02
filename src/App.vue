<script>
  import AppHeader from './components/header/AppHeader.vue';

  import Products from './components/Products.vue';

  import AppFooter from './components/footer/AppFooter.vue';
  export default {
    nome: 'Boolando',
    components: {
      AppHeader,
      Products,
      AppFooter
    },
  };
</script>

<template>
  
  <AppHeader/>

  <main>

    <Products/>

  </main>

  <AppFooter/>
</template>

<style>
</style>