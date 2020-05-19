<template>
    <div id="app">
        <Navbar/>
        <div>
            <Toolbar/>
            <Workspace/>
        </div>
    </div>
</template>

<script>
import Navbar from './views/Navbar.vue'
import Toolbar from './views/Toolbar.vue'
import Workspace from './views/Workspace.vue'

export default {
    name: 'App',
  components: {
    Navbar,
    Toolbar,
    Workspace
  }
}
</script>

<style>
html {
    overflow: hidden !important;
}
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;

    height: 100vh;
    width: 100vw;
    background-color: #0079bf;
    color: #ffffff;
    text-align: center;
}
</style>
