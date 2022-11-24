<template>
  <div class="prefooter">
    <div class="container">
      <img src="@/img/buy-comics-digital-comics.png" alt="">
      <span>digital comics</span>
      <img src="@/img/buy-comics-merchandise.png" alt="">
      <span>dc merchandise</span>
      <img src="@/img/buy-comics-subscriptions.png" alt="">
      <span>subscription</span>
      <img src="@/img/buy-comics-shop-locator.png" alt="">
      <span>dcomic shop locator</span>
      <img src="@/img/buy-dc-power-visa.svg" alt="">
      <span>dc power visa</span>
    </div>
  </div>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>
  .prefooter{
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #0282f9;
    height: 10rem;
  }

  img{
    width: 50px;
  }

  .container{
    width: 1200px;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  span{
    color: white;
    font-size: 18px;
    text-transform: uppercase;
  }
</style>
