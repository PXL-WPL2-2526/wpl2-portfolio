<script setup>

</script>

<template>
  <footer>
    <div class="gegevens">
      <div class="nummer">
        <img src="@/assets/icons/nummer.png" alt="telefoonnummer">
        <p>0478 10 23 52</p>
      </div>
      <div class="email">
        <img src="@/assets/icons/email.png" alt="email">
        <p>ottenmaxine@gmail.com</p>
      </div>
    </div>
    <div class="socials">
      <img src="@/assets/icons/instagram.png" alt="instagram">
      <img src="@/assets/icons/facebook.png" alt="facebook">
      <img src="@/assets/icons/pintrest.png" alt="pintrest">
    </div>

  </footer>
</template>

<style scoped>
footer{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 2rem;
  background: var(--beige);
  height: 607px;
}
footer p{
  font-size: 30px;
}
footer img{
  width: 60px;
}
.gegevens{
  display: flex;
  flex-direction: column;
  gap: 1rem;
}
.nummer, .email{
  display: flex;
  justify-content: left;
  align-items: center;
  gap: 1rem;
}
.socials{
  display: flex;
  justify-content: space-between;
  gap: 1rem;
  width: 407px;
}
</style>
