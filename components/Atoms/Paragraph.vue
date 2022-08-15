<template>
    <div class="">
        <p class="font-medium text-gray-400">{{text}}</p>
    </div>
</template>

<script>
export default {
    props:{
        text: {
            type: String,
            required: true,
        },
    }
}
</script>

<style>

</style>