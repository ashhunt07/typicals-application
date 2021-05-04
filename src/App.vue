<template>

  <Header />

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


<style scoped>
  @import './styles/main.css';
</style>