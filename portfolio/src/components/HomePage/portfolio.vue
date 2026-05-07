<script setup lang="ts">
</script>

<template>
  <div class="portfolio" id="portfolio">
    <div class="groen-vlak"></div>
    <h1>Portfolio</h1>
  </div>
</template>

<style scoped>
.portfolio{
  height: 100vh;
  display: flex;
  background-color: var(--beige);
}
.portfolio h1{
  font-size: 270px;
  font-weight: lighter;
  font-family: var(--font-family-aref);
  width: 70%;
  position: absolute;
  top: 250px;
  left: 490px;
  color: var(--dark-green);
}
.groen-vlak{
  width: 30%;
  background-color: var(--light-green);
}
</style>
