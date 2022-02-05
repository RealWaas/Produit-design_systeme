<template>
    <div class="Sign_In">
        <FormText tag="h1" text="Sign in"/>
        <h4>Not signed up ?</h4> <a>Register</a>
        <h3>Email</h3>
        <form>
          <input type="email" name="email" placeholder="johndoe@mail.com">

          <h3>Password</h3>
          <input type="password" name="email" placeholder="**********">
          <span>Forget password ?</span>
          <FormButton text="text" type="button" look="primary" size="medium" disabled="disabled"/>
        </form>
    </div>
</template>

<script>
import FormButton from '@/components/FormButton.vue'
import FormText from '@/components/FormText.vue'

export default {
  name: 'Signin',
  components: {
    FormButton,
    FormText
  },
}
</script>