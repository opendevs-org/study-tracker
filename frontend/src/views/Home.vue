<template>
  <div id="home-container" class="container-fluid p-5 d-flex align-items-center align-self-center justify-content-center">
    <div class="row align-items-center g-md-5">
      <div class="col-md-6 px-5">
        <h1 class="display-4 fw-bold lh-1 mb-3">
          What the heck is <br />
          Study Tracker?
        </h1>
        <p class="col-md-10 fs-4">
          An app that helps you plan your study goals for everyday. You can add hours towards each goal, time your hours spent using interactive buttons & see your study history of last 7 days!
        </p>
      </div>
      <div class="col-md-6 px-5">
        <Auth />
      </div>
    </div>
  </div>
</template>

<script>
import Auth from "../components/Auth.vue";
export default {
  name: "Home",
  components: {
    Auth,
  },
};
</script>
