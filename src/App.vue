<script>
import internal from 'stream'

export default {
  data() {
    return {

    }
  },
  methods: {

  }
}
</script>

<template>

<div class="wrapper">
  <div class="menu">
    <br>
    <h1 class="linear-gradient">EYOUNEED.COM</h1>
    <br>
       <div class="login">

       </div>
  </div>
</div>

</template>

<style scoped>
.menu {
  width: 100%;
  height: 10vh;
  position: fixed;
  align-content: center;
  align-items: center;
  align-self: center;
  margin: 0% -3%;
  color: black;
  background: -webkit-linear-gradient(0deg, #000000 0%, #48abe0 100%);
  background: -webkit-radial-gradient(
      circle,
      rgba(13, 8, 96, 1) 0%,
      rgba(9, 9, 121, 1) 21%,
      rgba(6, 84, 170, 1) 51%,
      rgba(0, 255, 113, 1) 80%
  );
  box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px, rgba(0, 0, 0, 0.12) 0px -12px 30px, rgba(0, 0, 0, 0.12) 0px 4px 6px, rgba(0, 0, 0, 0.17) 0px 12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;
}
body {
  font-family: sans-serif;
}

h1 {
  margin: 0 auto;
  font-size: 2rem;
}

h1.linear-gradient {
  background: -webkit-linear-gradient(
      90deg,
      rgba(13, 8, 96, 1) 0%,
      rgba(9, 9, 121, 1) 11%,
      rgba(6, 84, 170, 1) 11%,
      rgba(0, 155, 213, 100) 80%
  );
  font-weight: bold;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  max-width: max-content;
}
</style>
