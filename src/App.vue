<template>
  <div id="container">
    <app-user></app-user>
  </div>
</template>

<script>
  import User from './components/User.vue';
  export default {
    components: {
      'app-user': User
    }
  }
</script>

<style>

</style>
