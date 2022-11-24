<template>
  <footer>
    <div class="container">
      <h2>dc comics</h2>
      <ul>
        <li><a href="#">Characters</a></li>
        <li><a href="#">Comics</a></li>
        <li><a href="#">Movies</a></li>
        <li><a href="#">TV</a></li>
        <li><a href="#">Games</a></li>
        <li><a href="#">Videos</a></li>
        <li><a href="#">News</a></li>
      </ul>
      <h2>shop</h2>
      <ul>
        <li><a href="#">Shop DC</a></li>
        <li><a href="#">Shop DC Collectibles</a></li>
      </ul>
      <h2>dc</h2>
      <ul>
        <li><a href="#">Terms Of Use</a></li>
        <li><a href="#">Privacy policy (New)</a></li>
        <li><a href="#">Ad Choices</a></li>
        <li><a href="#">Advertising</a></li>
        <li><a href="#">Jobs</a></li>
        <li><a href="#">Subscription</a></li>
        <li><a href="#">Talent Workshops</a></li>
        <li><a href="#">CPSC Certificates</a></li>
        <li><a href="#">Ratings</a></li>
        <li><a href="#">Show Help</a></li>
        <li><a href="#">Contact Us</a></li>
      </ul>
      <h2>sites</h2>
      <ul>
        <li><a href="#">DC</a></li>
        <li><a href="#">MAD Magazine</a></li>
        <li><a href="#">DC Kids</a></li>
        <li><a href="#">DC Universe</a></li>
        <li><a href="#">DC Power Visa</a></li>
      </ul>
    </div>
  </footer>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>
  footer{
    background-image: url(@/img/footer-bg.jpg);
    background-position: center;
    background-size: cover;
    width: 100%;
    height: 30rem;
    display: flex;
    justify-content: center;
    flex-direction: column;
    flex-wrap: wrap;
  }

  h2{
    color: white;
    text-transform: uppercase;
    font-size: 20px;
  }

  ul{
    list-style: none;
  }

  a{
    text-decoration: none;
    color: gray;
  }

  .container{
    width: 1200px;
  }

</style>
