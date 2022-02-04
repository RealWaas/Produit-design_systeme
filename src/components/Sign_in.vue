<template>
    <div class="Sign_In">
        <h1>Sign in</h1>
        <h4>{{msg}}</h4> <a>Register</a>
        <ConnectForm/>
    </div>
</template>

<script>
import ConnectForm from '@/components/connexion-form.vue'

export default {
  name: 'Sign_in',
  components: {
    ConnectForm
  },
  props: {
    msg: String
  }
}
</script>