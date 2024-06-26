<template>
  <div>
    <NavBar />
    <Footer />
    <main class="container-fluid">
      <router-view />
    </main>
  </div>
</template>

<script>
import NavBar from "@/components/NavBar.vue";
import Footer from "@/components/Footer.vue"

export default {
  components:{
    NavBar,
    Footer
  },
};
</script>
<style src="@/assets/css/style.css"></style>
