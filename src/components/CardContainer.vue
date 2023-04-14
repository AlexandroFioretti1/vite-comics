<script>
import listCards from "../assets/data/dc-comics.json";
import CardVue from "./CardVue.vue";
export default {
  name: "CardContainer",
  data() {
    return {
      listCards,
    };
  },
  components: {
    CardVue,
  },
};
</script>

<template>
  <div class="d_flex">
    <CardVue v-for="card in listCards" :img="card.thumb" :title="card.series">
    </CardVue>
  </div>
</template>

<style>
.d_flex {
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
}
</style>
