<template>
  <div class="ui secondary pointing menu">
      <!-- <a href="/" class="active item"> -->
        <AppHeader/>
      <!-- </a> -->
  </div>
</template>

<script>
import AppHeader from './components/AppHeader'
export default {
    name: 'App',
    components: {
        AppHeader
    }
};
</script>