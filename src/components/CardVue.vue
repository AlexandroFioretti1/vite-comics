<script>
export default {
  name: "CardVue",
  props: {
    img: String,
    title: String,
  },
};
</script>

<template>
  <div class="w_f">
    <img class="img_fluid" :src="img" alt="img" />
    <h4>{{ title }}</h4>
  </div>
</template>

<style lang="scss" scoped>
.img_fluid {
  width: 100%;
  aspect-ratio: 1 / 1;
}
.w_f {
  width: calc(100% / 6);
}
</style>
