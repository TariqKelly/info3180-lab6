<template>
    <div class="news container">
        <h1 class="text-center text-success fw-bold">News</h1>
        <NewsList />
    </div>
</template>

<script>
import NewsList from '@/components/NewsList.vue'

export default {
    data () {
        return {};
    },
    components: { NewsList }
};
</script>

<style>
    
</style>