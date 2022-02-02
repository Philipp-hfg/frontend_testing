<template>
  <div class="header">
        <div class= "logo"><h1 class="Headline1">On</h1><h1 class="Headline2">Library</h1></div>
        <div class="data">
            <div class="eingabe">
                <h2>ISBN:</h2>
                <input id="ISBN" placeholder= "..." v-model="ISBN"/>
                <button class="getbook" v-on:click="fill"></button>
            </div>
            <div class="eingabe">
                <h2>Sprache:</h2>
                <input id="input" placeholder= "..."/>
            </div>
            <div class="eingabe">
                <h2>Folge/ Band:</h2>
                <input id="input" placeholder= "..."/>
            </div>
        </div>
  </div>
</template>

<script>

export default {
  name: 'AddBookForm',
  props: {
    data() {
    return {
      ISBN: '',
      };
    },
    methods: {
      addfunction() {
        },
      fill() {
        console.log(this.ISBN)
      }
    }
  }
}

</script>

<style scoped>

.getbook {
  height: 64px;
  width: 64px;
}

.header {
  float: left;
  width: 1920px;
  background-color: rgba(255, 255, 255, 0.8);
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-around;
  padding:0px;
  height:auto;
}

.logo {
  display: flex;
  width: auto;
  height: auto;
  margin-top: 35px;
}

.Headline1 {
  color: #537B8C;
  font-size: 64px;
  margin:0px;
}

.Headline2 {
  color: #2D2D2D;
  font-size: 64px;
  margin:0px;
}

.eingabe {
    display:flex;
    align-items: center;
    justify-content: flex-end;
    width: auto;
    height: auto;
    font-size: 24px;
    background-color: rgba(255, 255, 255, 0.5);
    padding: 0px;
    border-radius: 15px;
    margin-right: 972px;
}

h2 {
    margin: 0px;
    margin-right: 64px;
    text-align: left;
    width: 182px;
    font-weight: normal;
    font-size: 24px;
}

input {
  background: transparent;
  border:1px, solid, #2D2D2D;
  font-size: 24px;
  width: 608px;
  height: 64px;
  margin: 12px 0px;
  border-radius: 15px;
  padding: auto;
  padding-left: 24px;
  padding-right: 24px;
  
}
.data {
    width: 100%;
}
</style>