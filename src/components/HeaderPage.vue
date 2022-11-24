<template>
  <header>
    <div class="container">
      <div class="logo">
        <img src="@/img/dc-logo.png" alt="logo-dc">
      </div>
      <nav class="menu">
        <ul>
          <li><a href="#">characters</a></li>
          <li><a href="#">comics</a></li>
          <li><a href="#">movies</a></li>
          <li><a href="#">tv</a></li>
          <li><a href="#">games</a></li>
          <li><a href="#">collectibles</a></li>
          <li><a href="#">videos</a></li>
          <li><a href="#">fans</a></li>
          <li><a href="#">news</a></li>
          <li><a href="#">shop</a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>

  header{
    width: 100%;
    height: 7rem;
    background-color: white;
    display: flex;
    justify-content: center;
    position: fixed;
    top: 0;
    left: 0;
  }
  .container{
    display: flex;
    justify-content: space-between;
    width: 1200px;
  }

  img{
    width: 100%;
    height: 100%;
  }

  .logo{
    height: 100%;
  }

  ul{
    height: 100%;
    list-style: none;
    display: flex;
    align-items: center;
  }

  a{
    text-decoration: none;
    color: gray;
    text-transform: uppercase;
    font-weight: 900;
  }

  li{
    margin: 1rem;
    :hover{
      border-bottom: 2px solid blue;
    }
  }

</style>
