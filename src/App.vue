<template>
<div id="app">
    <HelloWorld msg="Welcome to Your Vue.js App" />
</div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
    name: 'App',
    components: {
        HelloWorld
    }
}
</script>

<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    /* text-align: center; */
    color: white;
    /* margin-top: 60px; */
    padding: 0;
    margin: 0;
}

body {
    background: #080808;
    padding: 0;
    margin: 0;
}
</style>
