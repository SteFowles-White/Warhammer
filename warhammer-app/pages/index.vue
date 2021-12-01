<template>
  <main>
    <section class="w-full relative heading">
      <div class="flex justify-between flex-wrap-reverse lg:flex-nowrap">
        <header class="flex items-center content-center justify-center w-full lg:w-4/12 lg:absolute heading__container p-8">
          <h1 class="text-8xl ml-8">War of the Gods</h1>
        </header>
        <picture class="w-full float-right rounded-tl-full">
          <source class="float-right lg:rounded-tl-full" media="(min-width:650px)" srcset="../static/images/Home-Battle-Image.jpg">
          <img
            class="float-right lg:rounded-bl-full w-full  lg:w-8/12"
            src="../static/images/Home-Battle-Image-mobile.jpg"
            alt="Epic battle with large armies"
          />
        </picture>
        </div>
    </section>
    <section class="container mx-auto pt-20 grid grid-cols-3 gap-4">
      <article>
        <header>
          <h2 class="text-4xl">History of the World</h2>
        </header>
        <div>
          <p>Discover about the world and its history. Add and edit the historical chronicals of the world</p>
          <div>
            <a href="">Location</a>
          </div>
        </div>
      </article>
      <article>
        <header>
          <h2 class="text-4xl">Play The Game</h2>
        </header>
        <div>
          <p>Want to continue your game and continue your epic adventure</p>
          <div>
            <a href="">Location</a>
          </div>
        </div>
      </article>
      <article>
        <header>
          <h2 class="text-4xl">View Rules and Army</h2>
        </header>
        <div>
          <p>Find out more about the ruls of the game</p>
          <div>
            <a href="">Location</a>
          </div>
        </div>
      </article>
    </section>
    <section class="container mx-auto pt-10">
      <header class="text-center pt-5 pb-5">
        <h2 class="text-4xl">Entering the World of Chaos & War</h2>
      </header>
      <p class="pt-3 tb-3 text-xl">
        This is a world of heros, Kings and Empires all fighting for different
        reason. At the begining of time the valar created a paradise of a world.
        Trees grew, the birds and animals thrived. Humans entere the world,
        primative in there knoweldge and content with a plentiful world provided
        by the valar and the Gods themselves, the Ilumita. For years they have
        built a world for all to enjoy and all to use, the Gods walked freely
        with the people bringing light and knowldge beyond compentions for the
        humans.
      </p>
      <p class="pt-3 tb-3 text-xl">
        It was in the year 1000 of the age of creation that a valar started to
        turn. This valar was named Melika, he was buetiful beyond compare, long
        blond/silver hair that flowed through the wind. Strenght, power and
        light shone form home such as the sun broke throught the darkness of the
        sun. However, many years in the age of creation had occoured and melkor
        grew ideas of his own.....
      </p>
      <div class="flex justify-center pt-8 pb-8">
        <a class="bg-yellow-500 p-4 rounded-lg" href="#">Find out about the history of creation</a>
      </div>
    </section>
  </main>
</template>

<script>
export default {};
</script>
<style scoped>

h1 {
    font-family: "Oxygen";
}

.heading {
  background-color: rgba(16, 38, 2, .1);
}
.heading__container{
    top: 17rem;
    left: 4rem;
    text-align: center;
    max-width: 35rem;
}

@media only screen and (max-width: 1400px) {
  .heading__container{
      top: 10rem;
      left: 0rem;
      max-width: initial;
      text-align: center;
  }
}

</style>
