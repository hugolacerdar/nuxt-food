<template>
  <main class="container">
    <AppHeader />
    <AppRestaurantInfo :dataSource="foodData" />
  </main>
</template>

<script>
import AppHeader from "@/components/AppHeader.vue";
import AppRestaurantInfo from "@/components/AppRestaurantInfo.vue";
import { mapState } from "vuex";

export default {
  computed: {
    ...mapState(["foodData"]),
  },
  components: {
    AppRestaurantInfo,
    AppHeader,
  },
};
</script>
