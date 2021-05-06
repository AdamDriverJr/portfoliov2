<template>
  <div id="contactbody">
      <div id="socials">
        <a href="https://www.linkedin.com/in/pakot-attila-089053206/" target="_blank">
        <v-img id="linkedin"
        :src="require('../assets/linkedin.svg')">
        </v-img>
        </a>
        <a href="https://www.instagram.com/pakot_attila/" target="_blank">
        <v-img id="instagram"
        :src="require('../assets/instagram.svg')"></v-img>
        </a>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
    #contactbody{
        height: auto;
        background-color: black;
    }
    #socials {
            display: flex;
            justify-content: space-around;
            margin-bottom: 100px;
            flex-direction: row;
            margin-top: 100px;

                #linkedin,#instagram {
                    max-height: 80px;
                    max-width: 80px;
                }
            }
</style>