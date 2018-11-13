<template>
  <div id="app">
    <app-header></app-header>
    <app-content></app-content>
    <app-footer></app-footer>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Footer from './components/Footer.vue';
import Content from './components/SignUp.vue';

export default {
  components: {
      'app-header': Header,
      'app-footer': Footer,
      'app-content': Content
  },
  data() {
    return {

    }
  },
  methods: {

  }
}
</script>

<style>
  body {
    background: #F4F4F4;
  }
  #app {
    width: 50%;
    height: 100vh;
    margin: 0 auto;
    background: white;
  }
</style>
