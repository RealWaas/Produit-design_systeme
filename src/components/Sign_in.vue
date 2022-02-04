<template>
    <div class="Sign_In">
        <h1>Sign in</h1>
        <h4>Not signed up ?</h4> <a>Register</a>
        <h3>Email</h3>
        <form>
          <input type="email" name="email" placeholder="johndoe@mail.com">

          <h3>Password</h3>
          <input type="password" name="email" placeholder="**********">
          <span>Forget password ?</span>
          <PrButton text="Sign in" type="button" backgroundColor="black" color="white"/>
        </form>
    </div>
</template>

<script>
import PrButton from '@/components/PrButton.vue'

export default {
  name: 'Signin',
  components: {
    PrButton
  },
}
</script>