<template>
  <div id="app">
<!--    <About/>-->
<!--    <PromoVideo/>-->
<!--    <PresidentMessage/>-->
    <OrganizingCommittee/>
<!--    <Socials/>-->
  </div>
</template>

<script>

import "../css/style.css"
// import PresidentMessage from "@/components/PresidentMessage";
// import About from "@/components/About";
import OrganizingCommittee from "@/components/OrganizingCommittee";
// import Socials from "@/components/Socials";
// import PromoVideo from "@/components/PromoVideo";
export default {
  name: 'App',
  components: {
    // PromoVideo,
    //
    // Socials,
    OrganizingCommittee,
    // About,
    // PresidentMessage,
  },
}
</script>

<style>
/*#app {*/
/*  font-family: Avenir, Helvetica, Arial, sans-serif;*/
/*  -webkit-font-smoothing: antialiased;*/
/*  -moz-osx-font-smoothing: grayscale;*/
/*  text-align: center;*/
/*  color: #2c3e50;*/
/*  margin-top: 60px;*/
/*}*/
</style>
