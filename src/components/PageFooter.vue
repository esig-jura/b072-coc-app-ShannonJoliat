<script setup>
defineProps({
    site: String
})

</script>

<template>
    <footer>
        &copy; 2023 -
        <a :href="site">
            Supercell.com
        </a>
    </footer>
</template>

<style scoped>

</style>