<template>
  <div id="app">
    <Header :menuLinks="menuLinks"/>
    <Main :comics="comics" />
    <SectionBlu />
    <Footer />
  </div>
</template>

<script>
import Footer from './components/Footer.vue';
import Header from './components/Header.vue';
import SectionBlu from './components/SectionBlu.vue';
import Main from './components/Main.vue';
import comicsJson from './jsons/dc-comics.json';

export default {
  name: 'App',
  components: {
    Header,
    Main,
    SectionBlu,
    Footer,
  },
  data: function() {
    return {
      comics: comicsJson,
      menuLinks: [
              {
                href: '#',
                name: 'CHARACTERS',
              },
              {
                href: '#',
                name: 'COMICS',
              },
              {
                href: '#',
                name: 'MOVIES',
              },
              {
                href: '#',
                name: 'TV',
              },
              {
                href: '#',
                name: 'GAMES',
              },
              {
                href: '#',
                name: 'COLLECTIBLES',
              },
              {
                href: '#',
                name: 'VIDEOS',
              },
              {
                href: '#',
                name: 'FANS',
              },
              {
                href: '#',
                name: 'NEWS',
              },
              {
                href: '#',
                name: 'SHOP',
              },
      ], 
    };
  },
};
</script>

<style lang="scss">
@import './style/app.scss';
</style>
