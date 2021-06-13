<template>
  <div id="app">
    <Nav />
    <modal-test />
    <alert-test />
  </div>
</template>

<script>
import 'bootstrap/scss/bootstrap.scss';
import Nav from './components/Nav.vue'
import ModalTest from './components/Modal.vue'
import AlertTest from './components/Alert.vue'

export default {
  name: 'App',
  components: {
    Nav,
    AlertTest,
    ModalTest,
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
