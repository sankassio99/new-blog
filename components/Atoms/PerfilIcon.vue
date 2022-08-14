<template>
    <div class="bg-gray-200 rounded-full w-20 h-w-20 overflow-auto">
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