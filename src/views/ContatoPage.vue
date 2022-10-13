<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>contato</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">contato</ion-title>
        </ion-toolbar>
      </ion-header>
    <div> Inseri uma div aqui</div>
    <ion-icon :icon="square"></ion-icon>
      <!-- weikw wesley -->
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';
import{square} from 'ionicons/icons';

export default  defineComponent({
  name: 'contatoPage',
  components: { IonHeader, IonToolbar, IonTitle, IonContent, IonPage },
  setup() {
    return{
      square,
    }
  }
});
</script>
