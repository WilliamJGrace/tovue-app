<template>
    <div>
        <h2>My todolist</h2>
        <Todo></Todo>
    </div>
</template>

<script>
    import Todo from './todo'

    export default {
        name: 'Todos',
        components: {
            Todo
        },
        props: [
            "todos"
        ]
        
    }
</script>

<style scoped>

</style>