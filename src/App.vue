<template>
  <div id="app">

    <one_direction/>
    <profile/>
    <about/>
    <founders/>
    <suscribe/>
    <footer_content/>
  </div>
</template>

<script>


import one_direction from "@/components/OneDirection";
import Profile from "@/components/Profile";
import About from "@/components/About";
import Founders from "@/components/Founders";
import Suscribe from "@/components/Suscribe";
import footer_content from "@/components/Footer_social";
export default {
  name: 'App',
  components: {
    footer_content,
    Suscribe,
    Founders,
    About,
    Profile,
    one_direction

  }
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
