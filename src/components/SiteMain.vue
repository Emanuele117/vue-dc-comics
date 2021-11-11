<template>
  <main>
    <div class="content">
      <p>--> Content goes here--</p>
    </div>
    <div class="icons-container">
      <div class="icons">
        <div class="icon">
          <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
          <p class="p-icon">DIGITAL COMICS</p>
        </div>
        <div class="icon">
          <img src="../assets/img/buy-comics-merchandise.png" alt="" />
          <p class="p-icon">DC MERCHANDISE</p>
        </div>
        <div class="icon">
          <img src="../assets/img/buy-comics-subscriptions.png" alt="" />
          <p class="p-icon">SUBSCRIPTION</p>
        </div>
        <div class="icon">
          <img src="../assets/img/buy-comics-shop-locator.png" alt="" />
          <p class="p-icon">COMIC SHOP LOCATOR</p>
        </div>
        <div class="icon">
          <img src="../assets/img/buy-dc-power-visa.svg" alt="" />
          <p class="p-icon">DC POWER VISA</p>
        </div>
      </div>
    </div>
  </main>
</template>

<script>
export default {
  name: "SiteMain",
};
</script>

<style lang= "scss">
$link-color: #0282f9;
.content {
  background-color: black;
  height: 150px;
  p {
    color: white;
    font-size: 30px;
    font-weight: bold;
    margin-left: 15rem;
  }
}
.icons-container {
  height: 200px;
  background-color: $link-color;
  .icons {
    display: flex;
    margin-left: 12rem;

    .icon {
      display: flex;
      height: 70px;
      margin-left: 5rem;
      margin-top: 3rem;
    }
    .p-icon {
      color: white;
      margin: 10px;
      margin-top: 30px;
    }
  }
}
</style>
