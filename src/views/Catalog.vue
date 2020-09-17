<template lang="pug">
    .catalog
        category-bar
        .catalog__inner
            h1.catalog__title Медицина
            .catalog__list
                <ProductItem />
                <ProductItem />
                <ProductItem />
                <ProductItem />
                <ProductItem />
                <ProductItem />
                <ProductItem />
                

</template>

<script>
import CategoryBar from "@/components/CategoryBar";
import ProductItem from "@/components/ProductItem";

export default {
  components: { CategoryBar, ProductItem }
};
</script>

<style lang="scss">
.catalog {
  width: 100%;
  position: relative;
  &__inner {
    padding: 16px 40px;
    margin: 0 auto;
    max-width: 1350px;
  }
  &__title {
    font-size: 5vw;
    margin: 3rem 0 0;
    margin-bottom: 0.5em;
    text-align: center;
  }
  &__list {
    display: flex;
    flex-wrap: wrap;
    margin-top: 3.5rem;
  }
}
</style>
