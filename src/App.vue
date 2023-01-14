<script>

import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter
  }
}



</script>

<template>
  <AppHeader />
  <AppMain />
  <AppFooter />

</template>

<style lang="scss">
@use './styles/general.scss' as *;
@use './styles/partials/variables' as *;
@import url('https://fonts.googleapis.com/css2?family=Lato&family=Montserrat&display=swap');
</style>
