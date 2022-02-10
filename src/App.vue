<template>
  <div class="min-h-screen  items-center sm:px-6 lg:px-20">
  <Navigation/>
  <Content/>
  <Footer/>
  </div>
</template>

<script>
import Navigation from "./components/navigation.vue";
import Content from "./components/content.vue";
import Footer from "./components/footer.vue"

export default {
  components: {
    Navigation,
    Content,
    Footer,
  }
}
</script>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}  */
.color {
  color: #4f5665;
}


.box {
  color: #ba55d3;
  border-color: #ba55d3;
}
.button {
  background-color: #ba55d3;
  border-color: #ba55d3da;
}
</style>
