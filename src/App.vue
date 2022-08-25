<template>
<meta name="google" content="translate">
<head>
<br><div class="disguise">
<a href="#about" class="disguise"> About |</a>
<a href="#proyects" class="disguise"> Proyects  |</a>
<a href="#studies" class="disguise"> Studies  |</a>
<a href="#testimonials" class="disguise"> Testimonials  |</a>
<a href="#working" class="disguise"> Interesting</a>
</div>
</head>
      <div>
          <label for="page-style" class="u-text--light">
            <input  type="checkbox" id="page-style" v-model="isDarkMode"/>
            <img class="sun" src="../src/assets/dark.png" alt="black">
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
