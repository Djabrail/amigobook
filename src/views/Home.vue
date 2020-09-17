<template>
  <div class="home">
    <CategoryBar />
  </div>
</template>

<script>
import CategoryBar from "@/components/CategoryBar";
export default {
  name: "Home",
  components: { CategoryBar }
};
</script>

<style scoped>
span {
  cursor: pointer;
}
</style>
