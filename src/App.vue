<script>
import AppHeader from './components/AppHeader.vue';
import AppFooter from './components/AppFooter.vue';
import AppMain from './components/AppMain.vue';
export default {
  components: {
    AppHeader,
    AppFooter,
    AppMain
  },
  data() {
    return {
      name: 'App'

    }
  }
}
</script>

<template>
  <AppHeader home="HOME" lifestyle="LIFESTYLE" stories="STORIES" pages="PAGES" aboutUs="ABOUT US"></AppHeader>
  <AppMain></AppMain>
  <AppFooter></AppFooter>
</template>

<style lang="scss" scoped></style>
