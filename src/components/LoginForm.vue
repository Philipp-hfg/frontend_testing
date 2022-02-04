<template>
  <div class="popup">
      <h2>E-Mail-Adresse</h2>
      <input id="email"/>
      <h2>Passwort</h2>
      <input id="paswort"/>
      <h3>Paswort vergessen?</h3>
      <button class="anmelden">Anmelden</button>
      <h3>Neu Registrieren</h3>
  </div>
</template>

<script>
export default {
  name: "LoginForm",
  props: {
      msg:String
  }
}


</script>

<style scoped>
</style>
