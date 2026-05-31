<script setup>
import Pijl from "@/components/Pijl.vue";
import Header from "@/components/Header.vue";

import Footer from "@/components/Footer.vue";

const headerTitle = "WPL1"
</script>

<template>
  <Pijl />
  <div id="pijlBoven">
    <Header :title="headerTitle"/>
  </div>

  <Footer />
</template>

<style scoped>

</style>
