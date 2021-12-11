<template>
  <div class="container">
    <Navigation />
    <Main />
  </div>
</template>

<script>
import Main from './Main.vue'
import Navigation from './Navigation.vue'
export default {
  components: { Navigation, Main },
  name: 'Dashboard',
  props: {
    msg: String
  }
}
</script>

<style scoped>
  .container{
    padding: 1em 1em 0;
    height: 100vh;
    overflow: hidden;
    display: flex;
  }
</style>
