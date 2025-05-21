# Vue-Whatsapp-FAB
Vue-Whatsapp-FAB é um componente Vue simples e personalizável que exibe um botão flutuante no canto inferior direito da tela, permitindo contato direto via WhatsApp.


## Install 
#### NPM 
Você pode instalar o componente via NPM (caso esteja publicado) ou simplesmente copiá-lo para seu projeto.
```bash 
npm install v-whatsapp-fab
``` 
 ## Uso

### Registro global 
``` js
import { createApp } from 'vue'
import App from './App.vue'
import VWhatsappFAB from 'v-whatsapp-fab'

const app = createApp(App)
app.component('VWhatsappFAB', VWhatsappFAB)
app.mount('#app')

``` 

### Uso no template:

```vue
<template>
  <v-app>
    <v-main>
      <router-view/>
      <VWhatsappFAB whatsapp_url="https://api.whatsapp.com/send?phone=0123456789"></VWhatsappFAB>
    </v-main>
  </v-app>
</template>
``` 

