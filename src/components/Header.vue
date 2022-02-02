<template>
  <div class="header">
        <div class= "logo"><h1 class="Headline1">On</h1><h1 class="Headline2">Library</h1></div>
    <div class="searchbar">
      <input id="input" placeholder="Alles durchsuchen...">
      <button class="search">
        <img src='./../assets/Lupe.png'/>
      </button>
    </div>
    <div class="btns">
    <button>
      <img src='./../assets/Home=Default.png'/>
    </button>
    <button>
      <img src='./../assets/MyLibrary=Default.png'/>
    </button>
    <button>
      <img src='./../assets/currency=Default.png'/>
    </button>
    <button>
      <img src='./../assets/profile=Default.png'/>
    </button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}

let buttons = document.querySelectorAll('button');

buttons.forEach(button => {
  button.addEventListener('click', function () {
    buttons.forEach(btn => btn.classList.remove('active'));
    this.classList.add('active')
  })
})

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.btns {
  display: flex;
  justify-content: space-evenly;
  gap: 64px;
  background-color: transparent;
}

.header {
  float: left;
  height: 176px;
  width: 1920px;
  background-color: rgba(255, 255, 255, 0.8);
  display: flex;
  align-items: center;
  justify-content: space-around;
  border-bottom: 1px solid #BFBFBF;
}

.searchbar {
  background-color: #C6C9CE;
  width: 632px;
  height: 52px;
  display:flex;
  align-items: center;
  justify-content: flex-end;
  border-radius: 15px;
}

input {
  background: transparent;
  border:transparent;
  font-size: 24px;
  width: 474px;
}

.search {
  align-content: center;
  width: 134px;
  height: 52px;
  font-size: 48px;
  background-color: rgba(255, 255, 255, 0.5);
  padding: 0px;
  border-radius: 15px;
}

.button_icon {
  height: 48px;
  width: 48px;
  color: black;
}

.logo {
  width: 287px;
  display: flex;
  margin-left: 148px;
}

.Headline1 {
  color: #537B8C;
  font-size: 64px;
}

.Headline2 {
  color: #2D2D2D;
  font-size: 64px;
}

button {
  height: 48px;
  width: 48px;
  cursor: pointer;
  outline: none;
  border: none;
  background-color: transparent;
  margin: 0px;
  padding: 0px;
}

</style>
