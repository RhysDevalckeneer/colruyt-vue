<template>
    <h1 class="font-bold text-2xl uppercase text-slate-800">🍕 {{ text }}</h1>
</template>

<script lang="ts">
export default {
    name: "Title",

    props: ['text']
}
</script>
