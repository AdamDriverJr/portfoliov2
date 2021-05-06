<template>
  <div class="black" id="landingbody">
    <div id="left">
      <h1 id="name">Hi,<br>I'm <span id="color">Attila Pakot.</span><br>I'm a Multimedia Designer.</h1>
    </div>
    <div id="right">
      <v-img id="me"
      :src="require('../assets/ME.jpg')"></v-img>
    </div>
  </div>
</template>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500&display=swap');

template {
    margin: 0;
    padding: 0;
    font-family: 'Montserrat', sans-serif;
    background-color: black;
  }

#landingbody {
  height: 100vh;
  display: flex;
  justify-content: space-between;
  padding: 200px;

}

#me{
    display: flex;
    height: 400px;
    width: 300px;
}

#name{
  font-size: 80px;
  color: white;
}

#color {
    color: #1A9161;
}

</style>

<script>

export default {
  name: 'Landing',
  

  components: {
    
  },

  data: () => ({
    //
  }),
};
</script>