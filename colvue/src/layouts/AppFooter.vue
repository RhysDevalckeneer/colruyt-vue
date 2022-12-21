<script lang="ts">
import AppContainer from './AppContainer.vue';

export default {

    components: {
        AppContainer
    },

    data() {
        let year = new Date().getFullYear();

        return {
            year
        }
    },

    mounted() {
        console.log('Hello from AppFooter!');
    },
}

</script>

<template>
    <footer class="bg-white py-4">
        <AppContainer>
            <div class="flex justify-between w-full">
                <div class="">
                    <p class="text-xs text-slate-400">&copy; {{ year }} Rhys Devalckeneer.</p>
                </div>
                <div class="">
                    <a href="" class="text-slate-400 text-xs underline mr-4">Privacy Policy</a>
                    <a href="" class="text-slate-400 text-xs underline">Terms of Service</a>
                </div>
            </div>
        </AppContainer>
    </footer>
</template>
