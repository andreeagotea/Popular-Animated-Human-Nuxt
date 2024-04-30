<template>
  <div class="home-container"></div>
</template>

<script>
export default {
  name: 'Home',
  props: {},
  head: {
    title: 'Popular Animated Human',
    meta: [
      {
        property: 'og:title',
        content: 'Popular Animated Human',
      },
    ],
  },
}
</script>

<style scoped>
.home-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
</style>
