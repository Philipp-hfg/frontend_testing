<template>
    <div class="sidebar">
        <div class="placeholder"></div>
        <div class="themes">
            <h3 class="first">Aktuell</h3>
            <h3>Alle</h3>
            <h3>Bestseller</h3>
            <h3>Neuheiten</h3>
        </div>
        <div class="genres">
            <h2>Genres</h2>
            <h3>Fantasy</h3>
            <h3>Science Fiction</h3>
            <h3>Cartoons und Comics</h3>
            <h3>Fachbücher</h3>
            <h3>Freizeit und Hobby</h3>
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

.sidebar {
    height: 1080px;
    width: 316px;
    background-color: #C6C9CE;
    float: left, top;
}

.placeholder {
    height: 176px;
}

.themes {
    text-align: left;
    margin-left: 24px;
}

.genres {
    text-align: left;
    margin-left: 24px;
    margin-top: 53px;
}

.first {
    margin-top: 64px;
}

h3 {
    font-weight: normal;
    font-size: 24px;
    line-height: 24px;
}

</style>