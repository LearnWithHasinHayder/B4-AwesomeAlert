<script setup>
    // defineProps([
    //     'heading',
    //     'message',
    //     'color'
    // ])

    defineProps({
        heading:{
            type:String,
            default:'Heading'
        },
        message:{
            type:String,
            default:'Message'
        },
        color:{
            type:String,
            default:'indigo'
        }
    })
</script>

<template>
    <div class="p-4 mb-4 text-sm rounded-lg dark:bg-gray-800" :class="`text-${color}-800 bg-${color}-50`" role="alert">
        <span class="font-medium"> {{ heading }}</span> {{ message }}
    </div>
</template>

<style scoped></style>