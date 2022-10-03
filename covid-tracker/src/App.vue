<template>
  <header-vue />
  <div class="container">
    <router-view/>
  </div>
</template>

<script lang="ts">
  import HeaderVue from './components/Header.vue';

  export default {
    components: {
      HeaderVue
    }
  }
  </script>