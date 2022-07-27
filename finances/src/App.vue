<template>
  <v-app>
        <v-tabs
        grow
        >
          <v-tab>Finanzas Personales</v-tab>
          <v-tab>Bonos y Fondos de Inversión</v-tab>
          <v-tab>Acciones</v-tab>
          <v-tab>Finanzas Empresariales</v-tab>
        </v-tabs>
        <div>
          <HelloWorld/>
        </div>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
