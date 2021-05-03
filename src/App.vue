<style>
  @import './assets/styles/main.css';
</style>

<template>

<Header />
<!-- <div class="container"> -->
  
<!-- </div> -->
</template>

<script>
import { Options, Vue } from 'vue-class-component';
import Header from './components/Header';

@Options({
  components: {
    Header
  },
})
export default class App extends Vue {}
</script>

