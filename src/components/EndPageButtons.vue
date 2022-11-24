<template>
  <div class="buttons">
    <div class="container">
      <button>sign-up now!</button>
      <div class="social">
        <span>follow us</span>
        <img src="@/img/footer-facebook.png" alt="">
        <img src="@/img/footer-twitter.png" alt="">
        <img src="@/img/footer-youtube.png" alt="">
        <img src="@/img/footer-pinterest.png" alt="">
        <img src="@/img/footer-periscope.png" alt="">
      </div>
    </div>
  </div>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>
  .buttons{
    background-color: #303030;
    display: flex;
    justify-content: center;
    padding: 1rem;
  }

  .container{
    width: 1200px;
    display: flex;
    justify-content: space-between;
  }

  button{
    color: white;
    text-transform: uppercase;
    border: 2px solid #0282f9;
    background-color: #303030;
    font-weight: 600;
    padding: .5rem;
  }

  .social{
    display: flex;
    gap: 1rem;
    align-items: center;
  }

  span{
    color: #0282f9;
    text-transform: uppercase;
    font-size: 25px;
    font-weight: 700;
  }
</style>
