<template>
  <div class="project-card point scale-up-center">
    <img :src="img" :alt="title" width="350" height="350" class="shadow" />
    <strong
      class="
        w-100
        p-1
        position-absolute
        start-50 top-50
        translate-middle
        text-center
        fs-5
        text-light
      "
    >
      <!-- <a :href="`/${title}`" class="sans"> {{ title }} </a> -->
      <h6 class="sans fs-5"> {{title}} </h6>
    </strong>
  </div>
</template> 
<script>
export default {
  props: ["img", "title", "project"],
};
</script>
<style scoped>
.project-card {
  width: 350px;
  height: 350px;
  overflow: hidden;
  position: relative;
  transition: 0.4s;
  background-color: rgba(0, 0, 0);
}
img {
  transition: 0.4s;
}
img:hover {
  transform: scale(1.1);
  opacity: 0.7;
}
strong {
  display: none;
}
.project-card:hover strong {
  display: block;
}
</style>