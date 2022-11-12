<script setup>
    const props = defineProps(['linkTitle', 'link'])
</script>

<template>
    <a :href="props.link" class="lg:text-lg flex items-center justify-center p-3 gap-2 text-slate-50 border-2 border-slate-300 rounded-xl bg-green-700 hover:bg-green-600 ease-linear duration-300" target="_blank
    "><slot></slot> {{ props.linkTitle }}</a>
</template>