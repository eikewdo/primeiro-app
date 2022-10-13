<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>test</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">test</ion-title>
        </ion-toolbar>
      </ion-header>
    
      <ExploreContainer name="test" />
    </ion-content>
  </ion-page>
</template>
   <!-- weikw wesley -->
<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';
import ExploreContainer from '@/components/ExploreContainer.vue';

export default  defineComponent({
  name: 'testPage',
  components: { ExploreContainer, IonHeader, IonToolbar, IonTitle, IonContent, IonPage }
});
</script>
