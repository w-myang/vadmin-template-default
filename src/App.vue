<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script setup>

</script>

<style lang="less">

.size{
  width: 100%;
  height: 100%;
}
html,body{
  .size;
  overflow: hidden;
  margin: 0;
  padding: 0;
}
#app {
  .size;
}
</style>
