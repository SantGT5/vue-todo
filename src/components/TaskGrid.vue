<template>
    <div class="task-grid">
        <template>
            <div v-for="(task, i) in tasks" :key="i">
                {{ task.name }}
            </div>
        </template>
    </div>
</template>

<script>
export default {
    props: {
        tasks: {type: Array, required: true}
    }
}
</script>

<style scoped>

</style>