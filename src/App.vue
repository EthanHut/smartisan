<template>
  <div id="app">
    <header-nav></header-nav>
    <router-view/>
  </div>
</template>

<script>
import headerNav from '@/components/header-nav.vue'
export default {
  name: 'App',
  components: {
    headerNav
  }
}
</script>

<style>

</style>
