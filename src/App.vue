<template>
  <div id="app" class="container">
    <Header />
    <Nav msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import Nav from './components/Nav.vue'
import Header from './components/Header.vue'
export default {
  name: 'app',
  components: {
    Nav, Header
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Gothic+A1|Love+Ya+Like+A+Sister&display=swap');
#app {
  font-family: 'Gothic A1', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
body {
  display: flex;
  justify-content: center;
}
.container {
    /* position: relative; */
    max-width: 860px;
    height: 100%;
    width: 100%;
  
    background-repeat: no-repeat;
}
</style>
