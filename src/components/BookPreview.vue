<template>
    <div class="grid">
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
</script>

<style scoped>

.grid {
    display: flex;
    height: 904px;
    width: 1604px;
    align-self: flex-end;
    float: right;
    margin: 0px;
    flex-wrap: wrap;
    justify-content: space-evenly;
}

.BookPreview {
    margin: 0px;
}

</style>