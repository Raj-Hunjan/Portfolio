<template>
<div>
  <Navigation/>
  <h1 class="head-two">Some of my work</h1>
  <div class="card">
    <article class="styles">
      <a href="https://raj-hunjan.github.io/cpnt201-a3/" class="link">
      <img class="some-image" src="assets/images/image-1.jpg" alt="laptop on desk">
      <div class="text">
        <h1 class="head-1">SVG logos</h1>
        <p class="p-1">Some SVG logos I made and customized</p>
      </div>
      </a>
    </article>

    <article class="styles">
      <a href="https://codepen.io/rajhunjann/full/porjVJp" class="link">
      <img class="some-image" src="assets/images/image-2.jpg" alt="Cool looking code">
      <div class="text">
        <h1 class="head-1">Landing page</h1>
        <p class="p-1">A landing page with a responsive nav bar that is animated</p>
      </div>
      </a>
    </article>

    <article class="styles">
      <a href="https://codepen.io/rajhunjann/full/jOLLNmJ" class="link">
      <img class="some-image" src="assets/images/image-3.jpg" alt="LED lamp">
      <div class="text">
        <h1 class="head-1">Random Fox API</h1>
        <p class="p-1">An API that display a random fox</p>
      </div>
      </a>
    </article>
  </div>
  <Footer/>
</div>
</template>

<style>

* {
box-sizing: border-box;
padding: 0;
margin: 0;
}

body {
  background-color: #18020C;
}

.card {
    margin: 40px;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-gap: 30px;
    justify-items: center;
    font-family: "Montserrat", sans-serif;
    font-weight: 300;
}

.card > .styles {
    background-color: #131314;
    box-shadow: 2px 2px 6px 0px rgba(0, 0, 0, 0.3);
    transition: transform .3s;
    border: none;
    border-radius: 20px;
    text-align: center;
    width: 300px;
}

.card > .styles:hover {
    transform: translateY(5px);
    box-shadow: 2px 2px 26px 0px rgba(144, 0, 163, 0.3);
}

.card > .styles .some-image {
    width: 100%;
    border-top-right-radius: 19px;
    border-top-left-radius: 19px;
}

.text {
    padding: 10px 20px 20px;
    color: ghostwhite;
    line-height: 2.3;
}

.text .head-1 {
    text-transform: uppercase;
}

.link {
  text-decoration: none;
}

@media (max-width: 700px) {
  .grid {
    grid-template-columns: repeat(1, 1fr);
  }

  .grid > .art {
    text-align: center;
  }
}

</style>