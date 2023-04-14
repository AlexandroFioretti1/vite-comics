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
  components:{
    CardVue
  }
};
</script>

<template>

  
<CardVue v-for="card in listCards" :img="card.thumb" :title="card.series"> </CardVue>


</template>

<style>
</style>
