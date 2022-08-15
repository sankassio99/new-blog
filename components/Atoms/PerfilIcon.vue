<template>
    <div class="bg-gray-200 rounded-full w-16 h-16 overflow-auto">
        <img :src="url" />
    </div>
</template>

<script>
export default {
    props:{
        url: {
            type: String,
            required: false,
        },
    }
}
</script>

<style>

</style>