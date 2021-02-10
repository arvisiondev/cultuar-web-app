<template></template>

<script>
export default {
  name: "ModelViewer",
  route: "assets/3d/",
  props: {
    slug: String,
    description: String,
  },
};
let start = "<model-viewer ";
let src = 'src="' + route + slug + '.glb"';
let iosSrc = 'ios-src="' + route + slug + '.glb"';
let description = 'description="' + description + '"';
let end = ``` auto-rotate
    ar
    ar-modes="scene-viewer quick-look webxr"
    ar-scale="auto"
    camera-controls
  ></model-viewer>```;

let model = start + src + iosSrc + end;
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
