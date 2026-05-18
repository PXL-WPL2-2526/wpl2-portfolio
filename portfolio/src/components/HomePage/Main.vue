<script setup>

</script>

<template>
  <main>
    <section class="richting">
      <h2>Waarom heb ik voor deze richting gekozen?</h2>
      <p>
        Ik koos voor deze richting omdat web development mij echt boeit. In het middelbaar volgde ik al een gelijkaardige opleiding, waardoor mijn interesse alleen maar groeide en ik zeker wist dat ik mij hierin verder wilde verdiepen. Het maken van websites vind ik bijzonder leuk om te doen en het geeft mij veel voldoening om iets functioneels van nul op te bouwen. Daarnaast spreekt ook de grafische wereld mij aan en combineert deze richting techniek en design op een manier die perfect bij mij past.
      </p>
    </section>

    <section class="vibes">
      <h2>My aesthetic</h2>
      <div class="afbeeldingen-vibes">
        <img class="foto1" src="@/assets/img/vibes1.jpg" alt="vibes foto 1">
        <img class="foto2" src="@/assets/img/vibes2.jpg" alt="vibes foto 2">
        <img class="foto3" src="@/assets/img/vibes3.jpg" alt="vibes foto 3">
      </div>
    </section>

    <section class="designer">
      <img src="@/assets/img/designer.jpg" alt="designer">
      <div class="designer-info">
        <h2>Waarom ben ik een goede designer?</h2>
        <p>
          Ik ben een goede designer omdat ik oog heb voor detail, structuur en gebruiksvriendelijkheid. Ik denk logisch na over hoe een website is opgebouwd en zorg ervoor dat alles duidelijk en overzichtelijk blijft. Door mijn interesse in web development combineer ik design met functionaliteit, zodat wat ik maak niet alleen mooi oogt, maar ook goed werkt.
        </p>
      </div>
    </section>

    <section class="button-skills">
      <a href="Skills.vue">Skills</a>
    </section>
  </main>
</template>

<style>
.richting{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin-bottom: 13rem;
}
.richting h2{
  font-size: 64px;
  text-align: center;
  margin-bottom: 5rem;
  width: 750px;
}
.richting p{
  font-size: 32px;
  width: 1000px;
  text-align: center;
}

.vibes{
  background-color: var(--beige);
  height: 1257px;
  margin-bottom: 13rem;
  display: flex;
  align-items: center;
  justify-content: center;
}
.vibes h2{
  font-size: 158px;
  font-family: var(--font-family-aref), sans-serif;
  width: 50px;
  position: absolute;
  top: 2850px;
  left: 240px;
}
.vibes img{
  border-radius: 40px;
}
.afbeeldingen-vibes{
  display: flex;
  align-items: center;
  gap: 4rem;
}
.foto1{
  width: 390px;
  height: 460px;
  position: relative;
  top: 200px;

}
.foto2{
  width: 527px;
  height: 870px;
}
.foto3{
  width: 390px;
  height: 460px;
  position: relative;
  top: -200px;
}

.designer{
  display: flex;
  justify-content: center;
  align-items: center;
  margin-left: 25rem;
  margin-bottom: 13rem;
}
.designer-info{
  background-color: var(--light-green);
  border-radius: 40px;
  height: 1000px;
  width: 800px;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding-left: 3rem;
}
.designer-info h2{
  font-size: 64px;
  color: var(--beige);
  text-align: center;
  margin: 7rem 0 5rem 0;
  width: 750px;
}
.designer-info p{
  font-size: 40px;
  color: var(--beige);
  width: 600px;
  text-align: center;
  margin-bottom: 5rem;
}
.designer img{
  width: 507px;
  height: 845px;
  border-radius: 40px;
  position: absolute;
  left: 330px;
}
.button-skills{
  display: flex;
  justify-content: center;
  align-items: center;
  margin-bottom: 13rem;
}

.button-skills a{
  text-decoration: none;
  font-size: 128px;
  font-family: var(--font-family-aref), sans-serif;
  color: var(--dark-green);
  border: 7px solid var(--dark-green);
  padding: 2rem 4rem;
  border-radius: 40px;
}
</style>
