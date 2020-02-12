<template>
  <div class="dash">
    <DashboardMenu/>
    <DashboardNavBar/>
  </div>
</template>

<script>
// @ is an alias to /src
import DashboardMenu from "@/components/DashboardMenu.vue";
import DashboardNavBar from "@/components/DashboardNavBar.vue";

export default {
  name: "Dashboard",
  components: {
    DashboardMenu,
    DashboardNavBar
  }
};
</script>