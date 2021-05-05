<template> 
    <footer>
        <Nav />
    </footer>
</template>

<script>
    import Nav from './Nav';
    
    export default {
        name: 'Footer',
            components: {
            Nav
            },
    }
</script>

<style scoped>
    @import '../styles/footer.css';
</style>

