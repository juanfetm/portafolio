<template>
  <div :class="getTheme()">
    <router-view />

    <nav class="nav-bar">
      <div><Icon class="juan-logo" icon="mdi:alpha-j-circle-outline" /></div>
      <div class="nav-bar__right">
      </div>
    </nav>

    <footer class="u-background-2 main-footer">
      <div class="main-footer__logo">
        <Icon class="juan-logo" icon="mdi:alpha-j-circle-outline" color="white" />
        <div>
          <label for="page-style" class="u-text--light">
            dark mode💡
            <input type="checkbox" id="page-style" v-model="isDarkMode"/>
          </label>
        </div>
      </div>

    </footer>
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue';
import { Icon } from '@iconify/vue';

const isDarkMode = ref(false);
function getTheme() {
  return isDarkMode.value ? 'theme--dark' : 'theme--light';
}
</script>
