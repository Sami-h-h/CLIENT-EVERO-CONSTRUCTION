<template>
  <div class="w-fit" :style="`width:${w}px;`">
    <img
      v-if="white"
      src="/logo-white.png"
      alt="EVERO CONSTRUCTION"
      class="shadow img-fluid"
    />

    <img
      v-else
      src="/assets/logo.png"
      alt="EVERO CONSTRUCTION"
      class="shadow img-fluid"
    />
  </div>
</template>
<script>
export default {
  props: ["w", "white"],
};
</script>
<style scoped>
div {
  /* width: 150px; */
  overflow: hidden;
}
img {
  transform: scale(1.5);
}
</style>