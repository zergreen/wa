<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->

  <!-- <div>
    hello my friend
  </div> -->

  <!-- <DataTable></DataTable> -->

  <MyTable></MyTable>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import DataTable from './views/DataTable.vue';
import MyTable from './views/MyTable.vue';

export default {
  name: 'App',
  components: {
    // HelloWorld,
    // DataTable
    MyTable
  }
}
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
