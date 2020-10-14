
<template>
  <div class="index">
    <dc-viewer
      viewer-id="viewer-container"
      @on-viewer-created="viewerCreatedHandler"
    >
      <dc-base-layer
        layer-type="google"
        :options="{ style: 'img' }"
      ></dc-base-layer>
    </dc-viewer>
  </div>
</template>

<script>
export default {
  name: 'Index',
  components: {},
  methods: {
    viewerCreatedHandler(viewer) {
    }
  }
}
</script>

<style lang="scss" scoped>
.index {
  width: 100%;
  height: 100%;
  overflow: hidden;
}
</style>
