<template>
  <ContentComponent/>
  <FooterComponent/>
</template>

<script>
import { defineComponent } from 'vue';
import ContentComponent from '../components/ContentComponent.vue';
import FooterComponent from '../components/FooterComponent.vue';

export default defineComponent({
  name: 'HomeView',
  components: {
    ContentComponent,
    FooterComponent,
  },
});
</script>

<style lang="scss">
@import "../assets/styles/main.scss";
</style>
