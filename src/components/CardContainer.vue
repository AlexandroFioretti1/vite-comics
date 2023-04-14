<script>
import listCards from "../assets/data/dc-comics.json";
export default {
  name: "CardContainer",
  data() {
    return {
      listCards,
    };
  },
};
</script>

<template>
  <span>{{ listCards[0].thumb }}</span>
</template>

<style></style>
