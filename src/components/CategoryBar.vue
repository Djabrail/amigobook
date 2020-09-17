<template lang="pug">
.category
    .category__list
        a.category__item(href="") Бизнес
        a.category__item(href="") Маркетинг
        a.category__item(href="") Продажи
        a.category__item(href="") Психология
        a.category__item.category__item--active(href="") Медицина
        a.category__item(href="") Религия
        a.category__item(href="") Детям
        a.category__item(href="") Клиссика
</template>

<style lang="scss">
.category {
  background: #fff;
  position: relative;
  width: 100%;
  &__list {
    margin: 0 auto;
    max-width: 1350px;
    padding: 0 40px;
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    height: 3rem;
    line-height: 3rem;
    position: relative;
  }
  &__item {
    &--active {
      font-weight: 400;
      color: #666;
      text-decoration: none;
    }
  }
}
</style>
