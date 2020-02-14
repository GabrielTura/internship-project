<template>
  <div class="dashboard">
    <div class="columns">
      <DashboardMenu />
      <div class="column dashNav">
        <DashboardNavBar />
        <DashboardNavBarMessage />
        <DashboardMain />
        <DashboardFooter />
      </div>
    </div>
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

<!-- @ is an alias to /src -->
<style src="@/scss/_DashboardFooter.scss" lang="scss"></style>
<style src="@/scss/_DashboardMain.scss" lang="scss"></style>
<style src="@/scss/_DashboardMenu.scss" lang="scss"></style>
<style src="@/scss/_DashboardNavBar.scss" lang="scss"></style>
<style src="@/scss/_DashboardNavBarMessage.scss" lang="scss"></style>
<style src="@/scss/_Footer.scss" lang="scss"></style>
<style src="@/scss/_FormLogin.scss" lang="scss"></style>
<style src="@/scss/_NavBar.scss" lang="scss"></style>