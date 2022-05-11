<template>
  <div id="bapp">
     <vue3-flip-countdown
      class="countdown"
      deadline="2022-06-03 16:00:00"
      countdownSize="5rem"
      mainColor="hotpink"
      secondFlipColor="hotpink"
      :labels="{days: 'Dagar',hours: 'Timmar',minutes: 'Minuter',seconds: 'Sekunder'}"
      labelColor="rebeccapurple"
      mainFlipBackgroundColor="linear-gradient(hotpink 20%, rebeccapurple)" 
      secondFlipBackgroundColor='linear-gradient(rebeccapurple, hotpink)'
      :flipAnimation="true"/>
    <div class="image"></div>
  </div>
</template>

<script>


</script>

<style>
#bapp {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background: linear-gradient(#648aad 25%, rebeccapurple 75%, hotpink );
}
.image {
  border-radius: 5px;
  height: 70vh;
  aspect-ratio: 1160 / 773 ;
  background: url('https://i.imgur.com/FRpAdMY.png');
  background-size: cover;
  background-repeat: no-repeat;
  box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.5);
}

html,body {
  margin: 0;
}

</style>
