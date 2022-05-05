<template>
  <div id="app">
     <vue3-flip-countdown deadline="2022-06-17 16:00:00"
     countdownSize="10rem"
     mainColor="white"
     :flipAnimation="true"/>
  </div>
</template>

<script>


</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  display: grid;
  place-items: center center;
  height: 100vh;
}

html,body {
  margin: 0;
}

</style>
