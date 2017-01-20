<template>
  <header class="container">
    <div class="logo">
      (logo)
    </div>
    <nav class="nav">
      <ul>
        <li>Articles</li>
        <li>Sermons</li>
        <li>Books</li>
        <li>Features</li>
        <li>Donate</li>
      </ul>
    </nav>
    <div>(Search)</div>
  </header>
</template>

<style scoped>
.container {
  display: flex;
  height: 63px;
  line-height: 63px;
  box-shadow: 0 0 7px 0 rgba(0,0,0,0.3);
  position: fixed;
  width: 100%;
  top: 0;
  left: 0;
  background-color: #fff;
}

.logo {
  font-weight: bold;
}

.nav {
  flex: 1;
  text-align: center;
}
.nav ul li {
  display: inline-block;
  padding: 0 16px;
}
</style>
