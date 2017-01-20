<template>
   <section class="container">
      <img src="/assets/opportunities-section.png" />
      <dg-button>Inquire</dg-button>
    </section>
</template>

<script>
import button from './button'

export default {
  components: {
    'dg-button': button
  }
}
</script>

<style scoped>
.container {
  text-align: center;
  padding-bottom: 80px;
}

img {
  display: block;
  margin: 0 auto 30px;
  width: 960px;
}
</style>
