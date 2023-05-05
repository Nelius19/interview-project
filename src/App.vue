<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <SignIn/>
  <!-- <SignUp/> -->
  <!-- <ResetPassword/> -->
  <!-- <AdminView/> -->

</template>

<script>
import SignIn from './components/SignIn.vue'
// import SignUp from './components/SignUp.vue'
// import ResetPassword from './components/ResetPassword.vue'
// import AdminView from './components/AdminView.vue'

export default {
  name: 'App',
  components: {
    SignIn,
    // SignUp,
    // ResetPassword,
    // AdminView
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

