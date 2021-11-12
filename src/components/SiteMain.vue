<template>
  <main>
    <div class="content">
      <div class="products">
        <product
          v-for="product in products"
          :key="product.series"
          :image="product.thumb"
          :titolo="product.series"
          :price="product.price"
        />
      </div>
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
import product from "./product.vue";

export default {
  components: {
    product,
  },
  name: "SiteMain",
  data() {
    return {
      products: [
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX",
          price: "$19.99",
          series: "Action Comics",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01",
          price: "$3.99",
          series: "American Vampire 1976",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb",
          price: "$16.99",
          series: "Aquaman",
          type: "graphic novel",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76",
          price: "$2.99",
          series: "Batgirl",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
          price: "$3.99",
          series: "Batman",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
          price: "$2.99",
          series: "Batman Beyond",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8",
          price: "$3.99",
          series: "Batman/Superman",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk",
          price: "$4.99",
          series: "Batman/Superman Annual",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8",
          price: "$5.99",
          series: "Batman: The Joker War Zone",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY",
          price: "$6.99",
          series: "Batman: Three Jokers",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX",
          price: "$4.99",
          series: "Batman: White Knight Presents: Harley Quinn",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq",
          price: "$16.99",
          series: "Catwoman",
          type: "graphic novel",
        },
      ],
    };
  },
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
  height: 160px;
  background-color: $link-color;
  margin-bottom: -19px;
  position: relative;
  .icons {
    display: flex;
    margin-left: 12rem;

    .icon {
      display: flex;
      height: 50px;
      margin-left: 3rem;
      margin-top: 3rem;
    }
    .p-icon {
      color: white;
      margin: 10px;
      margin-top: 20px;
      font-size: 12px;
    }
  }
}
</style>
