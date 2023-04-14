<template>
  <main>
    <section class="app_main d-flex justify-content-between align-items-center">
      <div class="container">
        <!-- primary container whit book-img and price -->
        <CardContainer></CardContainer>
        <!-- #end primary container whit book-img and price -->
      </div>
    </section>
        <!-- section whit icon  -->
    <section class="blue_container d-flex justify-content-between align-items-center">
      <div class="container d-flex justify-content-between align-items-center">
        <div>
          <img width="50" src="../assets/img/buy-comics-digital-comics.png" alt=""/>
          <a href="">DIGITAL COMICS</a>
        </div>
        <div>
          <img width="50" src="../assets/img/buy-comics-merchandise.png" alt=""/>
          <a href="">DC MERCHANDISE</a>
        </div>
        <div>
          <img width="50" src="../assets/img/buy-comics-subscriptions.png" alt=""/>
          <a href="">SUBSCRIPTION</a>
        </div>
        <div>
          <img width="30" src="../assets/img/buy-comics-shop-locator.png" alt="" />
          <a href="">COMIC SHOP LOCATOR</a>
        </div>
        <div>
          <img width="50" src="../assets/img/buy-dc-power-visa.svg" alt="" />
          <a href="">DC POWER E VISA</a>
        </div>
      </div>
    </section>
        <!-- #End section whit icon  -->
  </main>
</template>

<script>
import CardContainer from "./CardContainer.vue";
export default {
  components: { CardContainer },
  name: "SiteMain",
};
</script>

<style scoped lang="scss">
.app_main {
  background-color: black;
  color: white;
}
/* #End Main region  */
/* region bonus banner */
.blue_container {
  background-color: #0282f9;
  height: 150px;
}

main a {
  color: white;
  text-decoration: none;
}
</style>
