<template>
  <v-app>
     <v-main>
      <MenuLayout/>
      <AdminForm/>
    </v-main>
  </v-app>
</template>

<script>

import AdminForm from './components/AdminForm.vue';
import MenuLayout from './components/MenuLayout.vue';

export default {
  name: 'App',

  components: {
    AdminForm,
    MenuLayout,
  },

  data: () => ({
    //
  }),
};
</script>
