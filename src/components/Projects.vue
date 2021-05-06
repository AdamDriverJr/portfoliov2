<template>
    <div id="projectsbody">
        <div id="projectcards">
            <v-card
                class="mx-auto"
                max-width="700"
                max-height="1000"
                >
                    <v-img
                    class="white--text align-end"
                    height="200px"
                    :src="require('../assets/easv.jpg')"
                    >
                    <v-card-title>EASV app</v-card-title>
                    </v-img>
                    <v-card-text class="text--primary">
                    <div></div>
                    </v-card-text>

                    <v-card-actions>   
                    <v-btn
                        text
                        id="project1"
                        href="https://xd.adobe.com/view/151f3c1b-c454-4edc-b06b-e6dbe7229442-404c/?fullscreen&hints=off"
                        target="_blank"
                    >
                        Explore
                    </v-btn>
                    </v-card-actions>
                </v-card>
            </div>
        </div>
</template>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500&display=swap');

template {
    margin: 0;
    padding: 0;
    font-family: 'Montserrat', sans-serif;
    background: black;
  }

#projectsbody {
    height: auto;
    background-color: black;
}

.v-card__actions {
    align-items: center;
    display: flex;
    padding: 8px;
    margin-bottom: 30px;
}
</style>