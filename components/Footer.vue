<template>
  <footer>
    <div class="social">
      <NuxtLink class="icons" to="#"><font-awesome-icon :icon="['fab', 'instagram']"/></NuxtLink> 
      <NuxtLink class="icons" to="#"><font-awesome-icon :icon="['fab', 'github']"/></NuxtLink> 
      <NuxtLink class="icons" to="#"><font-awesome-icon :icon="['fab', 'linkedin']"/></NuxtLink> 
        <p class="email">
        rajhunjann@gmail.com
        </p> 
    </div>
      <ul class="list">
        <li><NuxtLink class="footer-text" to="/work">Work</NuxtLink></li>
        <li><NuxtLink class="footer-text" to="/about">About</NuxtLink></li>
        <li><NuxtLink class="footer-text" to="/contact">Contact</NuxtLink></li>
      </ul>
    <p class="copyright">
      &copy; This website is under a MIT license
    </p>
  </footer>
</template>

<style>

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

footer {
  font-family: 'Montserrat', sans-serif;
  font-weight: 300;
  background-color: #18020C;
  padding: 30px 0;
}

footer .social {
  text-align: center;
  padding-bottom: 25px;
  color: ghostwhite;
}

.email {
  padding-top: 15px;
  font-size: 18px;
}

footer .social .icons {
  font-size: 35px;
  color: #E0CA3C;
  margin: 12px;
}

footer .social .icons:hover {
  opacity: 0.7;
}

footer ul {
  list-style-type: none;
  margin-top: 0;
  padding: 0;
  font-size: 18px;
  line-height: 1.6;
  margin-bottom: 0;
  text-align: center;
}

footer ul li .footer-text {
  color: #6E44FF;
  text-decoration: none;
}

footer ul li {
  display: inline-block;
  padding: 0 11px;
}

footer ul li .footer-text:hover {
  opacity: 0.7;
}

footer .copyright {
  margin-top: 15px;
  text-align: center;
  color: ghostwhite;
  font-size: 15px;
}
</style>

<script>

</script>


