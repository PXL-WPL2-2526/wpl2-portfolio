<script type='js'>

</script>

<template>
  <nav>
    <ul>
      <li><a href="@/Skills.vue">Skills</a></li>
      <li><a href="@/realisaties.vue">Realisaties</a></li>
      <li><a href="@/Stage.vue">Buitenlandse stage</a></li>
    </ul>
  </nav>
</template>

<style scoped>
li{
  list-style: none;
}
nav{
  position: absolute;
  right: 70px;
  top: 30px;
}
nav ul{
  display: flex;
  gap: 5rem;
}
nav a{
  font-size: 30px;
  text-decoration: none;
  color: #434834;
}
a:hover{
  text-decoration: underline;
}
</style>
