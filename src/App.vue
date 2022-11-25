<template>
  <div>
    <HeaderPage />
    <ContentPage />
    <PreFooterPage />
    <FooterPage />
    <EndPageButtons />
  </div>
</template>

<script>
import HeaderPage from '@/components/HeaderPage.vue';
import ContentPage from '@/components/ContentPage.vue';
import PreFooterPage from '@/components/PreFooterPage.vue';
import FooterPage from '@/components/FooterPage.vue';
import EndPageButtons from '@/components/EndPageButtons.vue';

export default {
  components: {
    HeaderPage,
    ContentPage,
    PreFooterPage,
    FooterPage,
    EndPageButtons,
  },
};
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500;700;900&display=swap');

  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  html{
    font-family: 'Roboto', sans-serif;
  }
</style>
