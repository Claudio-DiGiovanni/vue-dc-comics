<!-- eslint-disable max-len -->
<template>
  <header>
    <div class="container">
      <div class="logo">
        <img src="@/img/dc-logo.png" alt="logo-dc">
      </div>
      <nav class="menu">
        <ul>
          <li v-for="eleMenu in arrMenu" :key="eleMenu.text"><a :href="eleMenu.url">{{ eleMenu.text }}</a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: 'HeaderPage',
  data() {
    return {
      arrMenu: [
        {
          url: '#characters',
          text: 'characters',
        },
        {
          url: '#comics',
          text: 'comics',
        },
        {
          url: '#movies',
          text: 'movies',
        },
        {
          url: '#tv',
          text: 'tv',
        },
        {
          url: '#games',
          text: 'games',
        },
        {
          url: '#collectibles',
          text: 'collectibles',
        },
        {
          url: '#videos',
          text: 'videos',
        },
        {
          url: '#videos',
          text: 'videos',
        },
        {
          url: '#fans',
          text: 'fans',
        },
        {
          url: '#shop',
          text: 'shop',
        },
      ],
    };
  },
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
    z-index: 10;
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
