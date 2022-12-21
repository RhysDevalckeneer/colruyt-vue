<script lang="ts">

  // import layouts
  import AppHeader from './layouts/AppHeader.vue'
  import AppFooter from './layouts/AppFooter.vue'
  import AppContainer from './layouts/AppContainer.vue';

  // import views
  import HomeView from './views/HomeView.vue';
  import AboutView from './views/AboutView.vue'
  import NotFoundView from './views/Error/NotFound.vue';

  export default {
    name: "App",
    components: {
      HomeView: HomeView,
      AboutView: AboutView,
      AppHeader: AppHeader,
      AppFooter: AppFooter,
      AppContainer: AppContainer,
      NotFoundView: NotFoundView
    },
  }
</script>

<template>
  <AppHeader />
    <AppContainer>
      <HomeView />
    </AppContainer>
  <AppFooter />
</template>
