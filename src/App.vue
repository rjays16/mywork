<template>
  <div id="app">
    <PresidentMessage/>
    <About/>
    <OrganizingCommittee/>
    <founders/>
    <suscribe/>
    <footer_content/>

  </div>
</template>

<script>

import PresidentMessage from "@/components/PresidentMessage";
import About from "@/components/About";
import Founders from "@/components/Founders";
import Suscribe from "@/components/Suscribe";
import footer_content from "@/components/Footer_social";
import OrganizingCommittee from "@/components/PromoVideo";
export default {
  name: 'App',
  components: {
    OrganizingCommittee,
    footer_content,
    Suscribe,
    Founders,
    About,
    PresidentMessage,
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
