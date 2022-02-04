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
          <button>Sign In</button>
        </form>
    </div>
</template>

<script>
export default {
  name: 'Signin'
}
</script>