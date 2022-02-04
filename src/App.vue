<template>
  <Signin/>
  <Signup/>
</template>

<script>
import Signin from './components/Sign_in.vue'
import Signup from './components/Sign_up.vue'

import './assets/styles/style.css';

export default {
  name: 'App',
  components: {
    Signin,
    Signup
  },
  methods: {
}
}
</script>