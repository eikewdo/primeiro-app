<template>
  <ion-page>
    <ion-tabs>
      <ion-router-outlet></ion-router-outlet>
      <ion-tab-bar slot="bottom">
        <ion-tab-button tab="fotoPage" href="/tabs/fotoPage">
          <ion-icon :icon="camera" />
          <ion-label>Foto</ion-label>
        </ion-tab-button>
          
        <ion-tab-button tab="tab2" href="/tabs/tab2">
          <ion-icon :icon="logoWindows" />
          <ion-label>Tab 2</ion-label>
        </ion-tab-button>
        
        <ion-tab-button tab="tab3" href="/tabs/tab3">
          <ion-icon :icon="logoWhatsapp" />
          <ion-label>Tab 3</ion-label>
        </ion-tab-button>
        <ion-tab-button tab="testPage" href="/tabs/testPage">
          <ion-icon :icon="logoTwitch" />
          <ion-label>test</ion-label>
        </ion-tab-button>
         <ion-tab-button tab="contatoPage" href="/tabs/contatoPage">
          <ion-icon :icon="callSharp" />
          <ion-label>contato</ion-label>
        </ion-tab-button>
      </ion-tab-bar>
    </ion-tabs>
  </ion-page>
</template>
   <!-- weikw wesley -->

<script lang="ts">
import { defineComponent } from 'vue';
import { IonTabBar, IonTabButton, IonTabs, IonLabel, IonIcon, IonPage, IonRouterOutlet } from '@ionic/vue';
import {  logoTwitch, logoWhatsapp, logoWindows, logoYoutube, callSharp,camera } from 'ionicons/icons';

export default defineComponent({
  name: 'TabsPage',
  components: { IonLabel, IonTabs, IonTabBar, IonTabButton, IonIcon, IonPage, IonRouterOutlet },
  setup() {
    return {
      
      logoTwitch,
      logoWhatsapp,
      logoWindows,
      logoYoutube,
      callSharp,
      camera,


    }
  }
});
const newLocal = "\u002f\u0074\u0061\u0062\u0073\u002f\u0063\u006f\u006e\u0074\u0061\u0074\u006f";
</script>
