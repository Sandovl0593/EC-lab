<template>
  <div class="about">
    {{ /*TODO: implementar esto */}}
    <HomeView />
  </div>
</template>

<script>
import HomeView from "./HomeView.vue";
export default {
  name: "AboutView",
  components: {
    HomeView,
  },
}
</script>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
