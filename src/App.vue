<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->

  <!-- <div>
    hello my friend
  </div> -->

  <!-- <DataTable></DataTable> -->

  <MyTable></MyTable>

  <MyAdd></MyAdd>

  <!-- <Home></Home> -->
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import DataTable from './views/DataTable.vue';
import MyTable from './views/MyTable.vue';
import MyAdd from './views/MyAdd.vue';
// import Home from './views/MyHome.vue';

export default {
  name: 'App',
  components: {
    // HelloWorld,
    // DataTable
    MyTable,
    MyAdd,
    // Home,
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
