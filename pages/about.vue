<template>
  <div>
    <Navigation/>
    <div class="about">
      <h1 class="head-two">
        A bit about me
      </h1>
      <section>
        <article>
          <p class="description">
            I just came out of the web developer program at SAIT <br> and  I knew nothing about web design or anything. <br>
            But for the past four months I've learned so much like <br> git, tailwindcss, nuxt.js and so much more! <br>
          </p>
          <p class="description-2">
            Now I'm looking forward to learning more <br> programming languages and frameworks like <br> react, and maybe wordpress. But we'll see.
          </p>
        </article>
      <img class="profile-pic" src="assets/images/raj.jpg" alt="My profile pic">
      </section>
    </div>
    <Footer/>
  </div>
</template>

<style>


.head-two {
  font-family: "Montserrat", sans-serif;
  height: 20vh;
  letter-spacing: 1px;
  background-image: url(https://media.giphy.com/media/aqS9Eew6JEvyL53pJE/giphy.gif);
  background-size: cover;
  color: transparent;
  background-clip: text;
  -webkit-background-clip: text;
  text-transform: uppercase;
  font-size: 50px;
  line-height: .95;
  padding: 30px 5rem;
  margin-top: 50px;
}

.description {
  color: ghostwhite;
  background-color: #131314;
  border-radius: 20px;
  font-family: "Montserrat", sans-serif;
  font-size: 20px;
  max-width: 80ch;
  margin-top: 0;
  padding: 20px
}

.description-2 {
  color: ghostwhite;
  background-color: #131314;
  border-radius: 20px;
  font-family: "Montserrat", sans-serif;
  font-size: 20px;
  max-width: 80ch;
  margin-top: 0;
  padding: 20px
}

section {
  display: flex;
  justify-content: space-around;
  line-height: 2.3;
}

.profile-pic {
  width: 450px;
  height: 500px;
  margin-bottom: 20px;
  padding: 10px;
  border-radius: 200px;
}
</style>