<template>
  <div class="ui container">
    <AppHeader />
    <router-view />
  </div>
</template>

<script>
import AppHeader from './components/AppHeader'
export default {
  name: 'App',
  components: {
    AppHeader
  }
  
}
</script>

<style scoped>

</style>