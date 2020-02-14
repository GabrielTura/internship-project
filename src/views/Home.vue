<template>
  <div class="home">
    <NavBar />
    <FormLogin />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import NavBar from "@/components/NavBar.vue";
import FormLogin from "@/components/FormLogin.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "Home",
  components: {
    NavBar,
    FormLogin,
    Footer
  }
};
</script>
