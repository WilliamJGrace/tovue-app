<template>
    <div>
        <form @submit="addTodo">
            <input type="text" v-model="title" name="title">
            <button type="submit">Add</button>
        </form>

    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

</style>