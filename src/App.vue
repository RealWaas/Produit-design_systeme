<template>
  <SignIn msg="Not signed up ?"/>
  <SignUp msg="Already got an account ?"/>
</template>

<script>
import SignIn from './components/Sign_in.vue'
import SignUp from './components/Sign_up.vue'

import './assets/styles/style.css';

export default {
  name: 'App',
  components: {
    SignIn,
    SignUp
  }
}
</script>