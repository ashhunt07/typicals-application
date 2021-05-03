<template> 
    <header>
        <img class="main-logo" src="/img/Clear_Design_mark_WHT.png" />
        <Nav />
        
        
    </header>
</template>

<script>
    import Nav from './Nav';

    export default {
        name: 'Header',
        components: {
            Nav
        }
    }
</script>