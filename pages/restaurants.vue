<template>
  <main class="container restaurant">
    <h1 class="title">Restaurants:</h1>
    <AppRestaurantInfo />
  </main>
</template>

<script>
import AppRestaurantInfo from "@/components/AppRestaurantInfo.vue";

export default {
  components: {
    AppRestaurantInfo,
  },
};
</script>

<style lang="scss" scoped>
.title {
  padding: 20px 200px;
}
</style>