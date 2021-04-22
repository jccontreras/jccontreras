<template>
  <div class="home" style="margin-top: auto">
    <img src="@/assets/me.jpeg" alt="Me" class="rounded-circle"
         style="max-height: 17%; max-width: 17%">
    <welcome-page/>
  </div>
</template>

<script>
// @ is an alias to /src
import WelcomePage from '../components/WelcomePage.vue';

export default {
  name: 'Home',
  components: {
    WelcomePage,
  },
};
</script>
