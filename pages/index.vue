<template>
  <section class="wrapper">
    <div>
      <h1 class="title text-center">
        nuxt-tailwind
      </h1>
      <Product />
      <Product />
    </div>
  </section>
</template>

<script>
import Product from "@/components/Product.vue"

export default {
  components: {
    Product
  }
}
</script>

<style scoped lang="scss">
.wrapper {
  min-height: 100vh;
  margin: 0 auto;
  background: lightgray;

  & .title {
    font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
      "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
    display: block;
    font-weight: 300;
    font-size: 40px;
    color: #35495e;
    letter-spacing: 1px;
    margin-bottom: 10px;
  }
}

</style>
