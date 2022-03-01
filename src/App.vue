<template>
  <ion-app>
    <MenuLayout></MenuLayout>
    <ion-router-outlet id="main-content" />
  </ion-app>
</template>

<script lang="ts">
import { IonApp, IonRouterOutlet } from '@ionic/vue';
import { defineComponent } from 'vue';
import MenuLayout from './components/layout/MenuLayout.vue';
export default defineComponent({
  name: 'App',
  components: {
    IonApp,
    IonRouterOutlet,
    MenuLayout
  }
});
</script>