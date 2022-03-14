<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" width="100px" />
    <div
      class="fb-login-button"
      data-width=""
      data-size="large"
      data-button-type="continue_with"
      data-layout="default"
      data-auto-logout-link="false"
      data-use-continue-as="false"
    ></div>
  </div>
</template>

<script>
// import { FB as VFacebookLogin } from "vue-facebook-login-component";

export default {
  name: "App",
  components: {},
};
</script>

<style >
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  display: flex;
  flex-direction: column;
  align-items: center;
}
</style>
