<template>
  <header>
    <div class="container h-100">
      <div class="d-flex justify-content-between align-items-center h-100">
        <div>
          <img class="py-2" src="../assets/img/dc-logo.png" alt="ImgLogo" />
        </div>
        <nav class="h-100 d-flex">
          <a class="d-flex align-items-center h-100" href="#">CHARACTERS</a>
          <a class="d-flex align-items-center h-100 c_blue" href="#">COMICS</a>
          <a class="d-flex align-items-center h-100" href="#">MOVIES</a>
          <a class="d-flex align-items-center h-100" href="#">TV</a>
          <a class="d-flex align-items-center h-100" href="#">GAMES</a>
          <a class="d-flex align-items-center h-100" href="#">COLLECTIBLES</a>
          <a class="d-flex align-items-center h-100" href="#">VIDEOS</a>
          <a class="d-flex align-items-center h-100" href="#">FANS</a>
          <a class="d-flex align-items-center h-100" href="#">NEWS</a>
          <a class="d-flex align-items-center h-100" href="#">SHOP</a>
        </nav>
      </div>
    </div>
  </header>
</template>
<script>
export default {
  name: "SiteHeader",
};
</script>

<style scoped lang="scss">
header {
  height: 130px;
}
nav > a {
  text-decoration: none;
  color: black;
  margin: 0rem 1rem;
}
.c_blue {
  color: #0282f9;
  box-shadow: inset 0 -3px 0 0 #0282f9;
}
</style>
