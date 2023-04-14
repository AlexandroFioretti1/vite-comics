<!-- script js -->
<script>
import SiteHeader from "./components/SiteHeader.vue";
import CardContainer from "./components/CardContainer.vue";
import SiteMain from "./components/SiteMain.vue";
import SiteFooter from "./components/SiteFooter.vue";
export default {
  data() {
    return {};
  },
  components: {
    SiteHeader,
    CardContainer,
    SiteMain,
    SiteFooter,
  },
};
</script>

<template>
  <SiteHeader></SiteHeader>

  <SiteMain></SiteMain>

  <SiteFooter></SiteFooter>
</template>

<style></style>
