<template>
  <div id="app">
   <router-view />
  </div>
</template>

<script>


export default {
  name:'App'

};
</script>


<style lang="scss">
body,html,#viewer-container{
  width: 100%;
  height: 100%;
  overflow: hidden;

}

</style>
<style lang="scss" scoped>

#app {
  width: 100%;
  height: 100%;
  overflow: hidden;
}

</style>

