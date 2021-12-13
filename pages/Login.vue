<template>
  <h1>Login</h1>
</template>

<script>
export default {
  name: "Login",
  mounted() {
    this.$auth.loginWith('oidc')
  }
}
</script>

<style scoped>

</style>
