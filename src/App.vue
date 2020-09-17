<template>
  <div id="app">
    <Header />
    <div class="wrapper">
      <router-view />
    </div>
  </div>
</template>

<script>
import "normalize.css";
import Header from "@/components/Header";

export default {
  components: { Header }
};
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;900&display=swap");
body {
  font-family: "Roboto", sans-serif;
}
a {
  color: #0072ff;
  border-color: rgba(0, 114, 255, 0.3);
}
</style>
