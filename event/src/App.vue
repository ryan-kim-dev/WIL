<template>
  <div>
    <ChildrenComponent></ChildrenComponent>
  </div>
</template>

<script>
import ChildrenComponent from './components/ChildrenComponent.vue';

export default {
  name: 'App',
  components: {
    ChildrenComponent,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
