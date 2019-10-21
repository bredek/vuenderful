<template>
  <div id="app">
    <Header />
    <router-view />
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/common/Header.vue';

export default {
  components: {
    Header,
  },
};
</script>

<style lang="scss">
body {
    padding-top: 5rem;
}
</style>
