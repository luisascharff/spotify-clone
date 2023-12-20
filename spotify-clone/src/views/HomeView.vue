<script setup>
    import HomeCard from '../components/HomeCard.vue';
</script>

<template>
    <div class="p-8">
        <button
            type="button"
            class="text-white text-2xl font-semibold hover:underline cursor-pointer"
        >
            Last Played
        </button>

        <div class="py-1.5"></div>

        <div class="flex items-center">
            <HomeCard image="./images/albumCovers/run_for_the_hills.png" size="300"  title="run for the hills - Techno Version" subTitle="Scammacist, Emilie Charlotte, Natalia Russo" />
            <HomeCard image="./images/albumCovers/reflections.png" title="Reflections (Sped Up)" subTitle="Scammacist, speedsongs>>, Nick Sterling" />
        </div>
    </div>


    <div class="p-8">
        <button
            type="button"
            class="text-white text-2xl font-semibold hover:underline cursor-pointer"
        >
        Recommended
        </button>

        <div class="py-1.5"></div>

        <div class="flex items-center">
            <HomeCard image="./images/albumCovers/smooth_operator.png" title="Smooth Operator - TikTok Remix" subTitle="Scammacist, Natalia Russo" />
        </div>
    </div>
</template>