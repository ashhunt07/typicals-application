<template> 
    <header>
      <nav class="navbar">
       <a class="navbar-brand" href="#">
        <img class="main-logo" src="/img/Clear_Design_mark_WHT.png" />
    </a>

        <Nav v-if="!mobileView"/>
        </nav>
    </header>
</template>

<script>
    import Nav from './Nav';
    
    export default {
        name: 'Header',
          components: {
            Nav
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
    }
</script>

<style scoped>
  @import '../styles/header.css';
</style>

