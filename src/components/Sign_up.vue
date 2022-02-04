<template>
    <div class="Register">
        <h1>Sign up</h1>
        <h4>{{msg}}</h4> <a>Sign in</a>
        <ConnectForm/>
    </div>
</template>

<script>
import ConnectForm from '@/components/connexion-form.vue'

export default {
  name: 'Sign_up',
  components: {
    ConnectForm
  },
  props: {
    msg: String
  }
}
</script>