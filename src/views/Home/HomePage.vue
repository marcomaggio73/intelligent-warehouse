<template>
  <master-layout pageTitle="Home Page">
    <div>Welcome Home Page!</div>
  </master-layout>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import {
  menuController,
} from "@ionic/vue";
export default defineComponent({
  methods: {
    openMenu() {
      menuController.open("app-menu");
    },
  },
  components: {
  },
});
</script>
