<template>
  <v-app>
      <NavBar />
      <Landing />
      <AboutMe />
      <Projects />
      <Contact />
  </v-app>
</template>

<script>

export default {
  name: 'App',

  components: {
    NavBar: () => import('@/components/NavBar'),
    Landing: () => import('@/components/Landing'),
    AboutMe: () => import('@/components/AboutMe'),
    Projects: () => import('@/components/Projects'),
    Contact: () => import('@/components/Contact'),
  },

  data: () => ({
    //
  }),
};
</script>

<style>
 html {
  scroll-behavior: smooth;
  
}
</style>
