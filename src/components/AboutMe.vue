<template>
  <div id="whole">
    <div id="main">
        <div class="text" id="aboutmetext" >
             <p>
    Hello, my name is Pakot Attila and i’m from Romania. I’m currently studying Multimedia Design at Erhvervsakademi Sydvest in Esbjerg. My goal is to learn and improve everyday, and make my work better quality day by day. After finishing with my studies i’m looking for a good work environment where i can be part of a team, and help the company succeed. Words that describe me are passionate, funny and friendly. My main hobbies are football and cooking. 
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