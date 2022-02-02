<template>
    <div class="grid" id="grid">
        <div class="BookPreview" id="output">
            <img src= API>
            <h2 class="title" placeholder="Titel"></h2>
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

//Jedes Buch erstellt sein eigenes Div
const preview = document.getElementById('grid')
const container = document.createElement('div')
preview.appendChild(container)

</script>

<style scoped>

.grid {
    display:flex;
    height: 1080px;
    width: 316px;
    background-color: #C6C9CE;
}

</style>