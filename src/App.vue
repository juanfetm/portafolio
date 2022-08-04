<template>
      <div>
          <label for="page-style" class="u-text--light">
            dark mode💡
            <input type="checkbox" id="page-style" v-model="isDarkMode"/>
          </label>
        </div>
          <div :class="getTheme()">
    <router-view />

    <nav class="nav-bar">
      <div><Icon class="juan-logo" icon="mdi:alpha-j-circle-outline" /></div>
      <div class="nav-bar__right">
      </div>
    </nav>

  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue';
// import { Icon } from '@iconify/vue';

const isDarkMode = ref(false);
function getTheme() {
  return isDarkMode.value ? 'theme--dark' : 'theme--light';
}
</script>

<style lang="scss">
@import "../src/assets/styles/main.scss";
</style>
