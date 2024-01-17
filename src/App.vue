<template>
  <LandingPage />
  <SecondPage />
  <ThirdPage />
</template>

<script>
import LandingPage from './components/desktop/LandingPage.vue';
import SecondPage from './components/desktop/SecondPage.vue';
import ThirdPage from './components/desktop/ThirdPage.vue';

export default {
  components: {
    LandingPage,
    SecondPage,
    ThirdPage,
  },
};
</script>