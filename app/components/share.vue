<template>
  <div class="container" v-on:click="toggleIcons">
    Share
    <div v-if="showIcons" class="icons">icons</div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      showIcons: false
    }
  },
  methods: {
    toggleIcons () {
      this.showIcons = !this.showIcons
    }
  }
}
</script>

<style scoped>
.container {
  cursor: pointer;
  width: 100px;
  position: relative;
}

.icons {
  background-color: #fff;
  box-shadow: 0 0 7px 0 rgba(0,0,0,0.3);
  width: 128px;
  height: 51px;
  margin-left: -50px;
  position: absolute;
  top: 100%;
  right: 0;
}
</style>
