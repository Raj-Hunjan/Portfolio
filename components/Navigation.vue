<template>
  <nav class="navbar">
  <div class="logo">
    <NuxtLink to="/"><svg viewBox="0 0 1211 1750" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path d="m0 0 200 95.8V859L0 962V0Z" fill="#E0CA3C"/>
      <path d="m0 758 200 95.8V1617L0 1748.5V758ZM0 221.8 85.5 41l761.7 360.3L761.7 582z" fill="#E0CA3C"/>
      <path fill="#E0CA3C" d="M647 400h200v449H647zM120 1049V849h727v200z"/>
      <path d="M44 961.8 261.7 895l582.7 590.7 2.2 263.5L44 961.8ZM847 1049V849h164v200zM1211 990.5l-200-95.8V131.5L1211 0v990.5Z" fill="#E0CA3C"/>
      <path d="m1211 1748.5-200-142v-717L1211 758v990.5Z" fill="#E0CA3C"/>
      </svg>
    </NuxtLink>
    </div>
  <ul class="navbar-links"> 
    <li><NuxtLink class="nav-text" to="/work">Work</NuxtLink></li>
    <li><NuxtLink class="nav-text" to="/about">About</NuxtLink></li>
    <li><NuxtLink class="nav-bubble" to="/contact">Contact</NuxtLink></li>  
  </ul>
 </nav>
</template>



<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
/*
body {
  background-color: #18020C;
}
*/
.logo {
  width: 50px;
  height: 50px;
  margin-bottom: 20px;
  margin-left: 10px;
}

nav {
    background-color: #6E44FF;
    font-family: 'Montserrat', sans-serif;
    font-weight: 500;
    font-size: 20px;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: center;
    padding: 15px;
  }

  nav ul {
    list-style-type: none;
    display: flex;
    flex-wrap: wrap;
    gap: 30px;
  }

.nav-text {
  text-decoration: none;
  color: #18020C;
  font-size: 21px;
}

.nav-text:hover {
  color: #FAFAFF;
}

.nav-bubble {
  text-decoration: none;
  color: #E0CA3C;
  font-size: 21px;
  background-color: #18020C;
  border-radius: 20px;
  padding: 11px 20px;
  margin-right: 10px;
}

.nav-bubble:hover {
  color: #6E44FF;
  background-color: #E0CA3C;
}
</style>