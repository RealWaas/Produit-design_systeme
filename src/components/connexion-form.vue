<template>
    <form>
          <h3>Email</h3>
          <input type="email" name="email" placeholder="johndoe@mail.com">

          <h3>Password</h3>
          <input type="password" name="email" placeholder="**********">
          <div class="registered" v-if="registered == 'true'">
            <span>Forget password ?</span>
          </div>
          <button>Sign In</button>
        </form>
</template>

<script>
export default {
  name: 'Connexion-form',
  props: {
    registered: String
  }
}
</script>