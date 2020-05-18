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
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    background-color: #0079bf;
    color: #ffffff;
}
</style>
