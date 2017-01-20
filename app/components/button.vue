<template>
  <button class="container">
    <slot>(NOPE)</slot>
  </button>
</template>

<style scoped>
.container {
  display: inline-block;
  margin: 0;
  padding: 13px 20px;
  font-style: normal;
  text-transform: uppercase;
  font-size: 10px;
  letter-spacing: 1px;
  text-align: center;
  background: #c6000e;
  color: #ffffff;
  border: none;
}
</style>
