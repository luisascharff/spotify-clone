<script setup>
    import CategorySelect from '../components/CategorySelect.vue';
</script>

<template>
    <div class="p-8">
        <button
            type="button"
            class="text-white text-2xl font-semibold hover:underline cursor-pointer"
        >
            Browse All
        </button>

        <div class="py-1.5"></div>

        <div class="grid xl:grid-cols-5 lg:grid-cols-4 md:grid-cols-3 sm:grid-cols-2 gap-6">
            <CategorySelect category="Podcasts" />
            <CategorySelect category="Hardstyle" />
            <CategorySelect category="Techno" />
            
        </div>
    </div>
</template>