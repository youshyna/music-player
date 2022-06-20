<template>
  <MainMenu />
  <BottomPlaybar />
</template>

<script setup>

import MainMenu from '@/components/MainMenu';
import BottomPlaybar from '@/components/BottomPlaybar';

</script>


<style lang="scss">

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  height: 100vh;
  background: #121216;
  color: white;
}

</style>
