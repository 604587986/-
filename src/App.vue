<template>
  <div id="app">
    <myheader></myheader>
    <keep-alive>
      <router-view></router-view>
    </keep-alive>
    <myfooter></myfooter>
    <navbar></navbar>
  </div>
</template>
<script>
import Myheader from "@/components/header.vue";
import Myfooter from "@/components/footer.vue";
import Navbar from "@/components/navbar.vue";

export default {
  components: {
    Myheader,
    Myfooter,
    Navbar
  }
};
</script>

<style>

</style>
