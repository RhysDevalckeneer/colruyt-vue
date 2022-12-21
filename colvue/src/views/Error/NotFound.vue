<script lang="ts">
export default {
    name: "NotFound",
}
</script>

<template>
    <main>
        <div class="flex items-center justify-center h-[86vh] flex-col">
            <p class="font-bold text-slate-700 text-2xl">404 - Page Not Found</p>
            <a href="/" class="bg-blue-500 text-white font-semibold py-2 px-3 rounded mt-4">
                <Icon icon="ion:arrow-back" />Go back
            </a>
        </div>
    </main>
</template>
