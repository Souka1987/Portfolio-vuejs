<template>
  <div id='q-app' class="background">
    <router-view/>
  </div>
</template>
<script>
export default {
  name: 'App'
}
</script>
<style lang="scss">
.background {
  background: url('~assets/Space-Wallpaper.jpg');
  background-size: cover;
  height: 100%;
  overflow: hidden;
}
</style>
