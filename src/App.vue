<template>
  <div id="app">
    <InfiniteScroll class="infi-scroll"> </InfiniteScroll>
  </div>
</template>

<script>
import InfiniteScroll from "./components/InfiniteScroll";

export default {
  name: "App",
  components: {
    InfiniteScroll,
  },
};
</script>

<style lang="scss">
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  margin-top: 60px;

  .infi-scroll {
    margin: 60px;
    height: 50%;
  }
}
</style>
