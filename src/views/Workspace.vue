<template>
    <div class="workspace">
        <div v-for="list in lists" :key="list" class="list-wrapper">

            <div class="list">
                <h1>{{ list.title }}</h1>
                <button class="button">
                    <i class="fas fa-plus"></i> Add a card
                </button>
            </div>

        </div>
    </div>
</template>

<script>
export default {
    name: 'Workspace',
    data() {
        return {
            lists: [
                {
                    title: "To Do"
                },
                {
                    title: "Doing"
                },
                {
                    title: "Done"
                }
            ]
        }
    }
}
</script>

<style scoped>
.list {
    background-color: #ebecf0;
    color: #172b4d;
}

.list-wrapper {
    width: 272px;
    display: inline-block;
}

.workspace {
    text-align: left;
}
</style>
