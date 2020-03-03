<template>
    <div>
        <div v-for="category in categories" :key="category.id">
            {{ category.name }}
        </div>
    </div>
</template>

<script>
    export default {
        name: "CategoryManager",
        props: ['categories']
    }
</script>

<style scoped>

</style>
