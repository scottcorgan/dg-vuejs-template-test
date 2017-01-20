<script>
  import header from './header'
  import footer from './footer'
  import careers from './careers'
  import recentFeatures from './recentFeatures'

  export default {
    components: {
      'home-header': header,
      'home-footer': footer,
      careers,
      'recent-features': recentFeatures
    }
  }
</script>

<template>
  <div class="container">
    <home-header></home-header>
    <main role="main">
      <careers></careers>
      <recent-features></recent-features>
    </main>
    <home-footer></home-footer>
  </div>
</template>

<style scoped>
main {
  padding-top: 63px;
}
</style>
