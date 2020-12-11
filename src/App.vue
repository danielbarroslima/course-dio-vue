<template>
  <div id="app">
    <ButtonVue></ButtonVue>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import ButtonVue from './components/ButtonVue';

export default {
  name: 'App',
  components: {
    ButtonVue,
  }
};
</script>

<style lang="scss">
#root {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
