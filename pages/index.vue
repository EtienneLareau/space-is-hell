<template>
  <div>
    <section>
        <div>
            <h1>SPACE IS HELL</h1>
            <h2 class="centre">A HARD LIFE AMONGST THE STARS</h2>
        </div>
    </section>
    <article>
      <Intro />
      <Where />
      <Frontier />
    </article>
    <div class="more">
      <GunsNow />
    </div>
    
  </div>
   
</template>

<script>
export default {}
</script>

<style scoped>
section {
    width: 100%;
    height: 100vh;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background: url('~assets/images/alienmain.webp') no-repeat top center;
    background-size: cover;
}

.more {
  width: 100%;
    height: 100%;
    /* min-height: 100vh; */
    display: flex;
    justify-content: center;
    align-items: center;
    background: url('~assets/images/starfield.jpg') no-repeat top center;
    background-size: cover;
    padding-top:100px;
}

h1 {
    font-weight: 400;
    color: #53746b;
    color: #fff;
    font-size: 4rem;
    text-shadow: 2px 2px 3px #53746b;
    padding: 0 25px;

    font-family: montserrat, sans-serif;

    font-weight: 700;

    font-style: normal;
}
h2 {
    color: #53746b;
    font-size: 2rem;
    text-shadow: 1px 1px 5px #fff;
    font-weight: 200;
    padding: 0 25px;
}

</style>
