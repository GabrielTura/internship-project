<template>
  <div class="dash">
    <DashboardMenu/>
    <DashboardNavBar/>
    <DashboardNavBarMessage/>
  </div>
</template>

<script>
// @ is an alias to /src
import DashboardMenu from "@/components/DashboardMenu.vue";
import DashboardNavBar from "@/components/DashboardNavBar.vue";
import DashboardNavBarMessage from "@/components/DashboardNavBarMessage.vue";

export default {
  name: "Dashboard",
  components: {
    DashboardMenu,
    DashboardNavBar,
    DashboardNavBarMessage
  }
};
</script>