<template>
  <section class="wrapper">
    <main class="font-sans text-grey-darkest tracking-wide flex-auto w-full container max-w-xl mx-auto py-5 md:py-16 px-6">
      <Intro />
      <About />
      <!-- <Product /> -->
    </main>
  </section>
</template>

<script>
import Intro from "@/components/Intro.vue"
import About from "@/components/About.vue"
import Product from "@/components/Product.vue"

export default {
  components: {
    Product,
    Intro,
    About
  }
}
</script>

<style scoped lang="scss">
.wrapper {
  min-height: 100vh;
  margin: 0 auto;

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
