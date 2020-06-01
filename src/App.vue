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

.button {
    background-color: rgba(255, 255, 255, 0.3) !important;
    margin: 0.2rem 0 0.2rem 0.2rem;
}
.input {
    background-color: rgba(255, 255, 255, 0.3) !important;
    margin: 0.2rem 0 0.2rem 0.2rem;
}
</style>
