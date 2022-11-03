<script setup>
    const props = defineProps([
        'url'
    ])
</script>

<template>
    <a :href="props.url"
        class="flex sm:inline-flex justify-center items-center bg-gradient-to-tr from-indigo-500 to-purple-400 hover:from- hover:to-purple-500 active:from-indigo-700 active:to-purple-600 focus-visible:ring ring-indigo-300 text-white font-semibold text-center rounded-md outline-none transition duration-100 px-5 py-2">
        <slot></slot>
    </a>
</template>
