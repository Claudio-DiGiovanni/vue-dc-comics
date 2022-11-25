<template>
  <footer>
    <div class="container">
      <div class="link-footer">
        <ul>
          <li><h2>dc comics</h2></li>
          <li><a href="#">Characters</a></li>
          <li><a href="#">Comics</a></li>
          <li><a href="#">Movies</a></li>
          <li><a href="#">TV</a></li>
          <li><a href="#">Games</a></li>
          <li><a href="#">Videos</a></li>
          <li><a href="#">News</a></li>
        </ul>

        <ul>
          <li><h2>shop</h2></li>
          <li><a href="#">Shop DC</a></li>
          <li><a href="#">Shop DC Collectibles</a></li>
        </ul>

        <ul>
          <li><h2>dc</h2></li>
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

        <ul>
          <li><h2>sites</h2></li>
          <li><a href="#">DC</a></li>
          <li><a href="#">MAD Magazine</a></li>
          <li><a href="#">DC Kids</a></li>
          <li><a href="#">DC Universe</a></li>
          <li><a href="#">DC Power Visa</a></li>
        </ul>
      </div>
      <img src="@/img/dc-logo-bg.png" alt="">
    </div>
  </footer>
</template>

<script>
export default {
  name: 'FooterPage',
  data() {
    return {
      arrLink: [
        {
          title: 'dc comics',
          links: [
            {
              url: '#Characters',
              text: 'Characters',
            },
            {
              url: '#Comics',
              text: 'Comics',
            },
            {
              url: '#Movies',
              text: 'Movies',
            },
            {
              url: '#TV',
              text: 'TV',
            },
            {
              url: '#Games',
              text: 'Games',
            },
            {
              url: '#Videos',
              text: 'Videos',
            },
            {
              url: '#News',
              text: 'News',
            },
          ],
        },
      ],
    };
  },
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
  }

  h2{
    color: white;
    text-transform: uppercase;
    font-size: 20px;
  }

  ul{
    list-style: none;
    width: 120px;
  }

  a{
    text-decoration: none;
    color: gray;
    font-size: 20px;
  }

  .container{
    width: 1200px;
    height: 100%;
    display: flex;
    overflow: hidden;
    align-items: center;
  }

  .link-footer{
    width: 600px;
    height: 100%;
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    padding: 2rem;
  }

  img{
    width: 600px;
  }

</style>
