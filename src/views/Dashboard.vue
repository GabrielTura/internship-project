<template>
  <div class="dash">
    <DashboardMenu/>
    <DashboardNavBar/>
    <DashboardNavBarMessage/>
    <DashboardMain/>
    <DashboardFooter/>
  </div>
</template>

<script>
// @ is an alias to /src
import DashboardMenu from "@/components/DashboardMenu.vue";
import DashboardNavBar from "@/components/DashboardNavBar.vue";
import DashboardNavBarMessage from "@/components/DashboardNavBarMessage.vue";
import DashboardMain from "@/components/DashboardMain.vue";
import DashboardFooter from "@/components/DashboardFooter.vue";

export default {
  name: "Dashboard",
  components: {
    DashboardMenu,
    DashboardNavBar,
    DashboardNavBarMessage,
    DashboardMain,
    DashboardFooter
  }
};
</script>