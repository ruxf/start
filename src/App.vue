<template>
  <div id="app">
    <CardList />
  </div>
</template>

<script>
import CardList from './components/card-list.vue';

export default {
  name: 'app',
  components: {
    CardList,
  },
};
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
