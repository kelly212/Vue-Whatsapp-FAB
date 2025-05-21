<template xmlns:v-slot="http://www.w3.org/1999/XSL/Transform">
  <div>
    <v-container>
      <br>
      <div style="text-align: center">
        <h1>Vue Whatsapp FAB</h1>
        <p>
          Vue-Whatsapp-FAB é um componente Vue que adiciona um botão flutuante personalizável para contato direto via WhatsApp, ideal para sites e aplicações responsivas
        </p>
        <br>
      </div>
      <v-row>
        <v-col cols="12" v-for="(item, index) in 10" :key="index">
          <br>
        </v-col>
      
      </v-row>
    </v-container>
  </div>
</template>

<script>
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'HomeView',
  data:()=>({
  }),
});
</script>
