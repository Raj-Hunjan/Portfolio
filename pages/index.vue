<template>
  <div>
  <Navigation/>
  <div class="title">
    <h1>Hi I'm Raj Hunjan</h1>
  </div>
  <Footer/>
  </div>
</template>


<style>

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  background-color: #18020C;
}

.title {
  font-family: "Montserrat", sans-serif;
  text-align: center;
  color: #FFF;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
  letter-spacing: 1px;
}

h1 {
  background-image: url(https://media.giphy.com/media/ZXlaCCmz4XY5QgUEhw/giphy.gif);
  background-size: cover;
  color: transparent;
  background-clip: text;
  -webkit-background-clip: text;
  text-transform: uppercase;
  font-size: 110px;
  line-height: .95;
  margin: 10px 0;
}

</style>
<script>
export default {}
</script>
