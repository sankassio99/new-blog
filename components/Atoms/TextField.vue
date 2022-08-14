<template>
    <div class="p-3 rounded-xl bg-gray-50 w-full flex items-center">
        <i class="material-icons px-2">{{icon}}</i>
        <input :type="inputType" 
        class="outline-none bg-gray-50 w-full" 
        :placeholder="placeholder"/> 
    </div>
</template>

<script>
export default {
    props:{
        placeholder: {
            type: String,
            required: false,
        },
        icon: {
            type: String,
            required: false,
        },
        inputType: {
            type: String,
            required: false,
            default: 'text'
        },
    }
}
</script>

<style>

</style>