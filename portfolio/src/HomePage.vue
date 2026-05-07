<script setup>
import Nav from '@/components/Navigation.vue'
import Header from '@/components/HomePage/Header.vue'
import Main from '@/components/HomePage/Main.vue'
import Footer from '@/components/Footer.vue'
</script>

<template>
  <div class="bloem1">
    <img src="@/assets/img/bloem.png" alt="bloem">
  </div>
  <div class="bloem2">
    <img src="@/assets/img/bloem.png" alt="bloem">
  </div>
  <div class="bloem3">
    <img src="@/assets/img/bloem.png" alt="bloem">
  </div>
  <div class="pijl-boven">
    <a href="#portfolio"><img src="@/assets/icons/arrow-up.png" alt="pijl"></a>
  </div>
<Nav />
<Header />

<Main />

  <Footer />
</template>

<style scoped>
.bloem1{
  position: relative;
}
.bloem1 img{
  position: absolute;
  top: 50px;
  left: 100px;
  width: 407px;
  height: 547px;
}
.bloem2{
  position: relative;
}
.bloem2 img{
  position: absolute;
  top: 630px;
  left: 1450px;
  width: 407px;
  height: 547px;
  transform: scaleX(-1);
}
.bloem3{
  position: relative;
}
.bloem3 img{
  position: absolute;
  top: 70px;
  left: -400px;
  width: 407px;
  height: 547px;
  transform: scaleX(-1);
}
.pijl-boven{
  position: fixed;
}
.pijl-boven img{
  position: absolute;
  top: 950px;
  left: 1770px;
  width: 100px;
  height: 100px;
}
</style>
