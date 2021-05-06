<template>
  <div id="whole">
    <div id="main">
        <div class="text" id="aboutmetext" >
             <p>
    My name is Tamás Major and I'm a 20 year old multimedia design and communication student from Hungary, attending Business Academy SouthWest in Esbjerg, Denmark. I have a broad skillset of Adobe programmes, as well as coding skills. My favourite things to do are Web and App designs, and making them actually work. I'm always trying to come up with unique and imaginative approaches to my projects. I can work both alone and in a team. When it comes to teamwork I'm clear and honest with everyone. I'm team-minded, always respectful, I always have a positive mindset and I try to stay calm even in difficult situations. I cooporate well with teammates and collegues, I'm punctual and accurate.
  </p>
        </div>
    </div>
    <div id="video">
        <iframe src="https://www.youtube.com/embed/_NK68pLdN3s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
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

#whole{
      height: auto;
      background: black;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-direction: column;
  }
  
iframe {
      width: 958px; 
      height: 625px;
      margin-bottom: 150px;
    }

#aboutmetext {
    font-size: 16px;
    margin-bottom: 100px;
    margin-top: 100px;
    color: white;
    max-width: 1200px;
}
</style>