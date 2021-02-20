<template>
  <div>
    <header></header>
    <main></main>
    <footer></footer>
  </div>
</template>

<script>
import Header from '@/components/Layout/Header'
import Main from '@/components/Layout/Main'
import Footer from '@/components/Layout/Footer'
export default {
  name: 'Layout',
  // eslint-disable-next-line vue/no-unused-components
  components: { Footer, Main, Header }
}
</script>

<style scoped>
.container {
  width: 100%;
  height: 100%;
}
</style>
