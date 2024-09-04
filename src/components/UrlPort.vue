<template>
  <div>
    <h3>URL: {{ currentUrl }}</h3>
    <h3>Port: {{ currentPort }}</h3>
  </div>
</template>

<script>
export default {
  data() {
    return {
      currentUrl: '',
      currentPort: ''
    };
  },
  mounted() {
    this.currentUrl = window.location.href; // Get the full URL
    this.currentPort = window.location.port; // Get the port
  }
};
</script>

<style scoped>
/* Add any styles you want here */
</style>
