<template>

  <Header/>
  <FooterM v-if="mobileView"/>

</template>

<script>
import { Options, Vue } from 'vue-class-component';
import Header from './components/Header';
import FooterM from './components/FooterM';
@Options({
  components: {
    Header,
    FooterM
  },
  data: () => {
    return{
      mobileView: true
    };
  },
  methods: {
    handleView() {
      this.mobileView = window.innerWidth <= 700;
    }
  },
  created() {
    this.handleView();
  }
})
export default class App extends Vue {}
</script>


<style scoped>
  @import './styles/main.css';
</style>