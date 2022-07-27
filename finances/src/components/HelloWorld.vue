<template>
  <vue-scroll-snap :fullscreen="true">
        <div class="item pt-12" id="home">
          <div align="left" class="item pl-12 pt-12">
            <h2>FZ1006</h2>
            <h1>Finanzas personales y empresariales</h1>
          </div>
          <div align="left" justify="end" class="item pl-12 pt-12">
            <p>José Eduardo Cadena Bernal - A01704641</p>
          </div>
        </div>
        <div class="item" id="two">
          12345
        </div>
    </vue-scroll-snap>
</template>

<script>
  import VueScrollSnap from "vue-scroll-snap";
  export default {
    name: 'HelloWorld',
    components: {VueScrollSnap},
    data: () => ({
      ecosystem: [
        {
          text: 'vuetify-loader',
          href: 'https://github.com/vuetifyjs/vuetify-loader',
        },
        {
          text: 'github',
          href: 'https://github.com/vuetifyjs/vuetify',
        },
        {
          text: 'awesome-vuetify',
          href: 'https://github.com/vuetifyjs/awesome-vuetify',
        },
      ],
      importantLinks: [
        {
          text: 'Documentation',
          href: 'https://vuetifyjs.com',
        },
        {
          text: 'Chat',
          href: 'https://community.vuetifyjs.com',
        },
        {
          text: 'Made with Vuetify',
          href: 'https://madewithvuejs.com/vuetify',
        },
        {
          text: 'Twitter',
          href: 'https://twitter.com/vuetifyjs',
        },
        {
          text: 'Articles',
          href: 'https://medium.com/vuetify',
        },
      ],
      whatsNext: [
        {
          text: 'Explore components',
          href: 'https://vuetifyjs.com/components/api-explorer',
        },
        {
          text: 'Select a layout',
          href: 'https://vuetifyjs.com/getting-started/pre-made-layouts',
        },
        {
          text: 'Frequently Asked Questions',
          href: 'https://vuetifyjs.com/getting-started/frequently-asked-questions',
        },
      ],
    }),
  }
</script>
