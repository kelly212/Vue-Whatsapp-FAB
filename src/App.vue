<template>
  <v-app>
    <v-main>
      <router-view/>
      <VWhatsappFAB whatsapp_url="https://api.whatsapp.com/send?phone=5533226363"></VWhatsappFAB>
    </v-main>
  </v-app>
</template>

<script>

import VWhatsappFAB from "./components/VWhatsappFAB";

export default {
  name: 'App',
  components: {
    VWhatsappFAB,
  },
  data: () => ({
    //
  }),
}
</script>
