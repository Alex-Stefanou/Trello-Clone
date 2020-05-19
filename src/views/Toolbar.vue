<template>
    <div class="navbar is-transparent">
        <div class="navbar-menu">

            <div class="navbar-start">
                <button class="button">
                    boardName
                </button>
                <button class="button">
                    <i class="far fa-star"></i>
                </button>
                |
                <button class="button">
                    Personal
                </button>
                |
                <button class="button">
                    <i class="fas fa-lock"></i> Private
                </button>
                |
                <button class="button">
                    <i class="fas fa-user-circle"></i>
                </button>
                <button class="button">
                    Invite
                </button>
            </div>

            <div class="navbar-end">
                <button class="button">
                    <i class="fas fa-concierge-bell"></i> Butler
                </button>
                <button class="button">
                    <i class="fas fa-ellipsis-h"></i> Show Menu
                </button>
            </div>

        </div>
    </div>
</template>

<script>
export default {
    name: 'ToolBar'
}
</script>

<style scoped>
.navbar {
    background-color: transparent;
    min-height: 3rem;
}
</style>
