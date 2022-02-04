<template>
  <div class="background">
      <div class= "logo"><h1 class="Headline1">On</h1><h1 class="Headline2">Library</h1></div>
      <div class="grid">
        <h2>Registrieren</h2>
        <h3>E-Mail-Adresse:</h3>
        <input id="email"/>
        <h3>Passwort (mind. 6 Zeichen):</h3>
        <input id="passwort"/>
        <h3>Geburtsdatum:</h3>
        <div class="geburtsdatum">
            <input id="day"/><input id="month"/><input id="year">
        </div>
        <a>Mit Ihrer Anmeldung erklären Sie sich mit unseren Allgemeinen Geschäftsbedingungen einverstanden. <br/> Bitte lesen Sie unsere Datenschutzerklärung, unsere Hinweise zu Cookies und unsere Hinweise zu interessenbasierter Werbung.</a>
        <button class="weiter">Konto erstellen und weiter</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "RegisterForm",
  props: {
      msg:String
  }
}


</script>

<style scoped>
</style>
