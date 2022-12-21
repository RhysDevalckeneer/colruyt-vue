<script lang="ts">
    import AppContainer from './AppContainer.vue';
    import Title from '../components/Text/Title.vue';

    export default {
        name: "AppHeader",
        
        components: {
            AppContainer,
            Title,
        },
    };
</script>

<template>
    <header class="py-5">
        <AppContainer>
            <div class="flex justify-between">
                <div class="flex justify-between items-center">
                    <Title text="Mealection" />
                    <ul class="w-1/12">
                        <li>
                            <a href="/about" class="text-slate-400">About</a>
                        </li>
                    </ul>
                </div>
                <ul class="w-42 flex justify-between">
                    <li>
                        <a href="/login" class="font-semibold text-blue-500">Login</a>
                    </li>
                    <li>
                        <a href="" class="box-border ml-8 font-semibold text-white bg-blue-500 py-2 px-3 rounded-sm">Signup</a>
                    </li>
                </ul>
            </div>
        </AppContainer>
    </header>
</template>
