<template>
    <div class="navbar">
        <div class="navbar-menu">

            <div class="navbar-start">
                <button class="button">
                    <i class="fas fa-th"></i>
                </button>
                <button class="button">
                    <i class="fas fa-home"></i>
                </button>
                <button class="button">
                    <i class="fab fa-trello"></i> Boards
                </button>
                <input class="input"/>
            </div>

            <i class="fab fa-trello"></i> Trello

            <div class="navbar-end">
                <button class="button">
                    <i class="fas fa-plus"></i>
                </button>
                <button class="button">
                    <i class="fas fa-info-circle"></i>
                </button>
                <button class="button">
                    <i class="far fa-bell"></i>
                </button>
                <button class="button">
                    <i class="fas fa-user-circle"></i>
                </button>
            </div>

        </div>
    </div>
</template>

<script>
export default {
    name: 'Narbar'
}
</script>

<style scoped>
.navbar {
    background-color: rgba(0,0,0,0.15);
    min-height: 2.5rem;
}
</style>
