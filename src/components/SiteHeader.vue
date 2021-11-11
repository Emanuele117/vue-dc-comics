<template>
  <header>
    <div>
      <img src="../assets/img/dc-logo.png" alt="" />
      <div class="link">
        <a href="">CHARACTERS</a>
        <a href="" class="active">COMICS</a>
        <a href="">MOVIES</a>
        <a href="">TV</a>
        <a href="">GAMES</a>
        <a href="">COLLECTIBLES</a>
        <a href="">VIDEOS</a>
        <a href="">FANS</a>
        <a href="">NEWS</a>
        <a href="">SHOP</a>
        <span class="line"></span>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "SiteHeader",
};
</script>

<style lang= "scss">
$link-color: #0282f9;
header {
  width: 100%;

  div {
    display: flex;
    img {
      margin-left: 15rem;
      margin-top: 1rem;
    }
    .link {
      margin-left: 14rem;
    }
    a {
      color: black;
      margin: 10px;
      text-decoration: none;
      margin-top: 60px;
    }
    .active {
      color: $link-color;
    }
    .line {
      color: blue;
      width: 100px;
      height: 20px;
    }
  }
}
</style>
