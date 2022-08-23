<template>
  <NavBar/>
  <ContentComponent/>
  <FormComponent/>
  <FooterComponent/>
</template>

<script>
import { defineComponent } from 'vue';
import ContentComponent from '../components/ContentComponent.vue';
import FooterComponent from '../components/FooterComponent.vue';
import NavBar from '../components/NavBar.vue';
import FormComponent from '../components/FormComponent.vue';

export default defineComponent({
  name: 'HomeView',
  components: {
    ContentComponent,
    FooterComponent,
    NavBar,
    FormComponent,
  },
});
</script>

<style lang="scss">
@import "../assets/styles/main.scss";
</style>
